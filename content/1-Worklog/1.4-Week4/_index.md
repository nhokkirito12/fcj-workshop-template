---
title: "Week 4 Worklog"
date: 2026-05-11
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Week 4 Objectives:
* Manage Object Storage (Amazon S3) and automate data lifecycles.
* Protect data using encryption tools and S3 Bucket Policies.

### Tasks to be implemented this week:
| Day | Task | Start Date | End Date | References |
| --- | --- | --- | --- | --- |
| Mon | - Deep dive into Amazon S3 Storage Classes (Standard, IA, Glacier). | 11/05/2026 | 11/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | - Study S3 Versioning & Lifecycle Rules for cost optimization. | 12/05/2026 | 12/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | - **Hands-on:** <br>&emsp; + Create an S3 Bucket, configure Block Public Access. <br>&emsp; + Write a Bucket Policy to restrict access to internal IPs. | 13/05/2026 | 13/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Thu | - Learn about AWS KMS (Key Management Service) and Encryption at Rest. | 14/05/2026 | 14/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Fri | - **Hands-on:** <br>&emsp; + Create Customer Managed Keys (CMK). <br>&emsp; + Enable SSE-KMS encryption for S3. <br>&emsp; + Set a Lifecycle Rule to transition old objects to Glacier. | 15/05/2026 | 15/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Achieved Results for Week 4:
* Gained a thorough understanding of S3 storage tiers and utilized Lifecycle Rules to automate cost reduction for archived data.
* Completely secured the bucket from public data leakage via Block Public Access and strict JSON-based Bucket Policies.
* Successfully integrated AWS KMS to automatically apply Encryption at Rest using a custom-managed key.