---
title: "Week 10 Worklog"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
### Week 10 Goals:

* Architecture and implement the data telemetry gathering process using AWS IoT Core.
* Provision Amazon SQS as an intermediary queue to prevent message drop and ensure reliability.
* Configure a Telemetry Processor via AWS Lambda to handle incoming data streams and persist them to Amazon DynamoDB.

### Detailed Weekly Tasks:
| Day | Task Description | Start Date | Completion Date | References |
| --- | --- | :---: | :---: | --- |
| 64 | Provision AWS IoT Core resources. Create the IoT 'Thing' for vehicle representation and attach X.509 security certificates. | 19/06/2026 | 19/06/2026 | |
| 65 | Develop the Vehicle Simulator script, which simulates car telemetry and publishes MQTT messages to IoT Core. | 20/06/2026 | 20/06/2026 | |
| 66 | Create an AWS IoT Rule Engine configuration to filter and route real-time MQTT data efficiently. | 21/06/2026 | 21/06/2026 | |
| 67 | Provision an Amazon Standard SQS queue to act as a robust message broker for the telemetry pipeline. | 22/06/2026 | 22/06/2026 | |
| 68 | Deploy an AWS Lambda serverless function dedicated to extracting and parsing vehicle metrics from SQS arrays. | 23/06/2026 | 23/06/2026 | |
| 69 | Attach the SQS queue as an Event Source Mapping to the Lambda function, allowing it to process items in batches. | 24/06/2026 | 24/06/2026 | |
| 70 | Code the backend logic to parse the telemetry logs and permanently store the latest vehicle parameters inside Amazon DynamoDB. | 25/06/2026 | 25/06/2026 | |


### Achievements:

* Successfully established a secure end-to-end telemetry pipeline from the Simulator to AWS cloud components.
* Deployed a robust messaging system using an SQS buffer and Lambda event-driven processing.
* Reliably ingested and stored the sensor histories into the NoSQL DynamoDB database.
