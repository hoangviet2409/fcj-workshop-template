---
title: "T?ng quan v? Workshop"
date: 2026-07-09
weight: 1
chapter: false
pre: " <b> 5.1 </b> "
---

# T?ng quan v? Workshop

#### 1. B?i c?nh và V?n ð? (Context & Problem)
Vi?c qu?n l? phýõng ti?n giao thông (cá nhân, giao hàng, d?ch v?) theo cách th? công hi?n nay ðang g?p nhi?u h?n ch?. Ch? xe thý?ng xuyên quên l?ch b?o dý?ng ð?nh k?, khó theo d?i sát sao t?nh tr?ng hao m?n c?a các b? ph?n quan tr?ng, d?n ð?n nguy cõ hý h?ng n?ng gi?a ðý?ng ho?c gây m?t an toàn giao thông. Hõn n?a, vi?c không có cõ s? d? li?u lýu tr? l?ch s? v?n hành c?ng khi?n các doanh nghi?p v?n t?i g?p khó khãn trong vi?c t?i ýu hóa chi phí và tu?i th? c?a xe.

Ð? gi?i quy?t bài toán này, chúng ta c?n m?t h? th?ng có kh? nãng t? ð?ng hóa vi?c thu th?p d? li?u (telemetry) liên t?c t? các phýõng ti?n và x? l? thông minh ð? ðýa ra c?nh báo k?p th?i.

#### 2. M?c tiêu c?a Workshop (Workshop Objectives)
Thông qua workshop này, b?n s? t? tay xây d?ng ðý?c m?t h? th?ng **Smart Vehicle Management** hoàn ch?nh ?ng d?ng các d?ch v? ðám mây (Cloud) trên n?n t?ng AWS. Sau khi hoàn thành, b?n s? n?m b?t ðý?c:
* Cách k?t n?i các thi?t b? IoT v?i ðám mây thông qua giao th?c MQTT.
* K? nãng x? l? d? li?u th?i gian th?c (Real-time data processing) b?ng ki?n trúc Serverless.
* Cách thi?t k? cõ s? d? li?u NoSQL t?i ýu cho lu?ng d? li?u xe c?.
* Kh? nãng thi?t l?p h? th?ng giám sát và t? ð?ng kích ho?t c?nh báo thông minh qua Email/SMS.

#### 3. Ki?n trúc h? th?ng (System Architecture)

![architect](../../images/5-Workshop/5.1-Workshop-overview/architect.jpg)

Ki?n trúc c?a d? án ðý?c thi?t k? theo mô h?nh **Event-Driven** (Hý?ng s? ki?n) và **Serverless**, chia làm hai lu?ng x? l? ð?c l?p nhýng liên k?t ch?t ch? v?i nhau:

* **Lu?ng Telemetry (Dành cho xe):** 
  - Các thi?t b? g?n trên xe (ho?c Vehicle Simulator) s? liên t?c thu th?p d? li?u (v?n t?c, nhi?t ð?, qu?ng ðý?ng) và g?i tr?c ti?p lên **AWS IoT Core** thông qua MQTT. 
  - **IoT Rule** s? ðóng vai tr? ngý?i ði?u ph?i, t? ð?ng l?c và chuy?n ti?p các thông ði?p quan tr?ng này sang **AWS Lambda** ð? phân tích ngý?ng an toàn.
  - Sau khi x? l?, d? li?u s? ðý?c lýu tr? dài h?n vào **Amazon DynamoDB**.

* **Lu?ng Qu?n l? (Dành cho ngý?i dùng/Dashboard):** 
  - Ngý?i dùng ho?c ch? xe mu?n tra c?u thông tin b?o dý?ng s? s? d?ng ?ng d?ng web (Frontend).
  - ?ng d?ng này g?i các truy v?n (HTTP Requests) t?i **Amazon API Gateway**.
  - API Gateway ð?nh tuy?n các truy v?n ð?n m?t **AWS Lambda** ð?c l?p khác, chuyên trách vi?c ð?c/ghi d? li?u trên **DynamoDB** và tr? k?t qu? v? cho ngý?i dùng.

* **H? th?ng Giám sát & C?nh báo (Monitoring & Alerting):**
  - M?i ho?t ð?ng c?a h? th?ng ðý?c ghi log l?i trên **CloudWatch Logs** ð? thu?n ti?n cho vi?c g? l?i (debug).
  - Khi phát hi?n s? ki?n b?t thý?ng (ví d?: nhi?t ð? ð?ng cõ vý?t quá 105°C), **CloudWatch Alarm** s? l?p t?c b? kích ho?t và ra l?nh cho **Amazon SNS** g?i tin nh?n c?nh báo kh?n c?p ð?n thi?t b? c?a ch? xe.

Trong các ph?n ti?p theo, chúng ta s? ði sâu vào th?c hành cài ð?t t?ng thành ph?n trên!

