---
title: "Week 2 Worklog"
date: 2026-04-27
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Week 2 Objectives:
* Master core cloud networking architectures.
* Build an enterprise-grade isolated virtual network (VPC).

### Tasks to be implemented this week:
| Day | Task | Start Date | End Date | References |
| --- | --- | --- | --- | --- |
| Mon | - Understand Amazon VPC architecture, differentiate between Public and Private Subnets. | 27/04/2026 | 27/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | - Study Route Tables, Internet Gateway (IGW), and NAT Gateway concepts. | 28/04/2026 | 28/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | - **Hands-on:** <br>&emsp; + Provision a Custom VPC. <br>&emsp; + Configure 2 Public Subnets & 2 Private Subnets. <br>&emsp; + Attach an IGW and route traffic to the Internet. | 29/04/2026 | 29/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Thu | - Differentiate Security Groups (Stateful) and Network ACLs (Stateless). <br> - Learn network traffic monitoring via VPC Flow Logs. | 30/04/2026 | 30/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Fri | - **Hands-on:** <br>&emsp; + Provision a NAT Gateway for Private Subnets. <br>&emsp; + Deploy an EC2 instance to test internal routing. <br>&emsp; + Enable VPC Flow Logs. | 01/05/2026 | 01/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Achieved Results for Week 2:
* Successfully built a Multi-AZ VPC infrastructure with well-defined Public and Private subnet tiers.
* Configured Route Tables to accurately direct traffic between subnets, the IGW, and the NAT Gateway.
* Mastered instance-level firewall configurations using Security Groups to allow/deny specific port traffic (e.g., port 80, 22).
* Enabled VPC Flow Logs for proactive security analysis and network monitoring.