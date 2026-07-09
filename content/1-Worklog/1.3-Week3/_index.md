---
title: "Week 3 Worklog"
date: 2026-05-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---
### Aims for Week 3:

* Architect customized, sandboxed cloud network environments utilizing Amazon VPC.
* Segment structural IPs into logical Subnets and dictate traffic flows through dedicated Route Tables.
* Secure infrastructure boundaries rigorously via Security Groups and Network ACL definitions.

### Task Roadmap:
| Day | Work Performed | Start Date | Completion Date | Reference Materials |
| --- | --- | :---: | :---: | --- |
| 15 | Dove deep into Amazon VPC anatomy, studying CIDR block mathematics and internal IP addressing. | 01/05/2026 | 01/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 16 | Compared cloud security paradigms: The stateful nature of Security Groups against stateless NACLs. | 02/05/2026 | 02/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 17 | Explored complex hybrid cloud connectivity using Elastic Load Balancers, VPNs, and Direct Connect protocols. | 03/05/2026 | 03/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 18 | Provisioned an initial VPC from scratch, carving it into separate Public and Private networking subnets. | 04/05/2026 | 04/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 19 | Activated an Internet Gateway (IGW) and bound it to Public Route Tables to permit external outbound communication. | 05/05/2026 | 05/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 20 | Deployed a NAT Gateway component inside the public space to grant private servers safe internet patching access. | 06/05/2026 | 06/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 21 | Proved network security by writing manual deny rules into NACL and allowing specific inbound ports on Security Groups. | 07/05/2026 | 07/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |


### Results Accumulated:

* Assembled fully functional Virtual Private Clouds adept at isolating backend application data.
* Orchestrated seamless internet gateways providing granular control over instances communicating with the web.
* Prevented unauthorized entry into local instances by carefully balancing Security Group whitelisting with NACL blocking algorithms.
