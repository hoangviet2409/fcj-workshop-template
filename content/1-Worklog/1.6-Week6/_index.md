---
title: "Week 6 Worklog"
date: 2026-05-22
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---
### Week 6 Core Aims:

* Dive into scaling constraints and dedicated storage mechanisms mapped to EC2.
* Clarify the security obligations between the cloud provider and the tenant.
* Set up user authentication platforms via Cognito and activate system-wide auditing.

### Project Tracking:
| Day | Scheduled Activity | Start Date | Completion Date | Reference Link |
| --- | --- | :---: | :---: | --- |
| 36 | Review Amazon Machine Images (AMI) lifecycles and define automatic snapshot cycles using AWS Backup. | 22/05/2026 | 22/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 37 | Assess the differences between high-availability Amazon EBS disks and volatile local Instance Stores. | 23/05/2026 | 23/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 38 | Explore the Amazon EFS shared protocol and orchestrate elastic server expansions using EC2 Auto Scaling. | 24/05/2026 | 24/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 39 | Trace exactly where cloud responsibility ends and customer duty begins using the AWS Shared Responsibility Model. | 25/05/2026 | 25/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 40 | Harness Amazon Cognito to create Identity Pools, securing JWT token handshakes for application clients. | 26/05/2026 | 26/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 41 | Set up AWS Security Hub dashboards for continuous threat monitoring and capture administrative logs via CloudTrail. | 27/05/2026 | 27/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 42 | Sculpt precise IAM Execution Roles that allow Lambda functions to legally communicate with services like DynamoDB and SQS. | 28/05/2026 | 28/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |


### Major Conclusions:

* Proficient at assigning proper block-level (EBS) or file-level (EFS) data solutions dependent on operational demands.
* Confidently delineated my personal security duties from those managed internally by Amazon.
* Successfully generated authenticated application environments supervised actively by CloudTrail audit trails.
