---
title: "Week 7 Worklog"
date: 2026-05-29
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
### Main Goals for Week 7:

* Construct secure, high-capacity object storage repositories utilizing Amazon S3.
* Leverage S3 Static Website Hosting to properly expose web frontend assets.
* Introduce Amazon CloudFront CDN to drastically improve global page load times.

### Logged Weekly Activities:
| Day | Scheduled Task | Start Date | Completion Date | Reference Documentation |
| --- | --- | :---: | :---: | --- |
| 43 | Evaluate the economic differences between Amazon S3 Storage Classes (Standard, IA, Glacier). | 29/05/2026 | 29/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 44 | Provision basic S3 Buckets, turning on Public Access Block rules to prevent accidental exposure. | 30/05/2026 | 30/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 45 | Turn on the Static Website Hosting function on S3 to serve raw frontend HTML/JS files safely. | 31/05/2026 | 31/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 46 | Develop precise Cross-Origin Resource Sharing (CORS) rules and Bucket Policies governing the endpoints. | 01/06/2026 | 01/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 47 | Attach Amazon CloudFront distributions to the existing storage to cache web content near users. | 02/06/2026 | 02/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 48 | Restrict access to the S3 bucket using Origin Access Control (OAC), forcing all traffic through the CDN. | 03/06/2026 | 03/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 49 | Validate the caching hit responses via the final CloudFront URLs, and remove testing buckets. | 04/06/2026 | 04/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |


### Target Accomplishments:

* Guaranteed the integrity and security of massive-scale file storage using best practices in S3.
* Completed a fully operational frontend hosting infrastructure wrapped behind a fast CloudFront CDN.
* Exhibited strong competence in crafting fine-grained IAM Bucket Policies alongside OAC configuration.
