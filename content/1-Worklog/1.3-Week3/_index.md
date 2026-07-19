---
title: "Week 3 Worklog"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Week 3 Objectives:
* Ensure High Availability (HA) for server systems.
* Implement automated traffic distribution and Auto Scaling mechanisms.

### Tasks to be implemented this week:
| Day | Task | Start Date | End Date | References |
| --- | --- | --- | --- | --- |
| Mon | - Learn the principles of High Availability (HA) on AWS. | 04/05/2026 | 04/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | - Study Application Load Balancer (ALB) and Target Groups. | 05/05/2026 | 05/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | - Understand Amazon Auto Scaling Group (ASG) and Launch Templates. | 06/05/2026 | 06/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Thu | - Write Bash scripts (User Data) for automated Web Server deployment. <br> - Explore scaling strategies (Dynamic, Scheduled). | 07/05/2026 | 07/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Fri | - **Hands-on:** <br>&emsp; + Deploy ALB integrated with ASG inside the Custom VPC. <br>&emsp; + Configure Dynamic Scaling Policies. <br>&emsp; + Perform a CPU stress test. | 08/05/2026 | 08/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Achieved Results for Week 3:
* Automated the web environment configuration process using EC2 User Data scripts.
* Deployed an Application Load Balancer to smoothly distribute incoming HTTP traffic across multiple Availability Zones.
* Configured an Auto Scaling Group that successfully scaled out instances during CPU stress testing and scaled in when the load decreased.