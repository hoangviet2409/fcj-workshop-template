---
title: "Week 11 Worklog"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---
### Main Priorities for Week 11:

* Push the Frontend web assets to an S3 hosting bucket backed by global CloudFront caching.
* Solidify endpoint security using Amazon API Gateway combined with Cognito authentication tokens.
* Complete the core backend logic within AWS Lambda, tying it smoothly into Google's Gemini AI.

### Weekly Work Breakdown:
| Day | Development Task | Start Date | Completion Date | Reference |
| --- | --- | :---: | :---: | --- |
| 71 | Transferred the compiled production React/Next dashboard strings to an S3 Static Website. | 26/06/2026 | 26/06/2026 |  |
| 72 | Hardened frontend distribution by establishing a CloudFront CDN and Origin Access Control parameters. | 27/06/2026 | 27/06/2026 |  |
| 73 | Instantiated a Cognito User Pool to orchestrate the lifecycle of user identities and permissions. | 28/06/2026 | 28/06/2026 |  |
| 74 | Rolled out an API Gateway tier guarded rigorously by a Cognito Authorizer evaluating token validity. | 29/06/2026 | 29/06/2026 |  |
| 75 | Coded the central API Handler functionality via Lambda, capable of securely mutating DynamoDB items. | 30/06/2026 | 30/06/2026 |  |
| 76 | Injected the Gemini AI SDK into the Lambda function, creating a smart diagnostic engine for vehicle faults. | 01/07/2026 | 01/07/2026 |  |
| 77 | Tied the final API routes to the matching frontend UI blocks and prepared the platform for testing. | 02/07/2026 | 02/07/2026 |  |


### Key Achievements:

* Successfully brought the user-facing Dashboard online, served powerfully through CloudFront caching.
* Fenced the backend REST routes securely, accepting only strictly verified Cognito tokens.
* Accomplished advanced generative AI integration within a serverless Lambda, analyzing metadata in real-time.
* Wrapped up the entire coding phase of the program seamlessly.
