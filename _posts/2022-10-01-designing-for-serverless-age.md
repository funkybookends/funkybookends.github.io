---
layout: post
title:  "Designing for the Serverless Age"
tags: architecture
summary: Good architecture is driven by constraints, serverless has fundamentally changed them.
---

[Designing for the Serverless Age - Gojko Adzic](https://www.youtube.com/watch?v=w7X4gAQTk2E)

## My Take Aways

* Serverless challenges the way we architecture our applications. Solutions for the old constraints don't apply.
* Much of existing architecture practices are optimised for reserved resources. Severless means we can optimise for utilised capacity.
* So much complex code around state management etc is optimised for time to recover (if an instance of VM goes down). Serverless pushes us to optimise for time to start. Time to recover is not the same anymore.
* In severless we should design for "share nothing"
* It is now trivial, almost cost free, to run experiements, have as many environments as you want. It challenges the concepts of staging, pre-prod, shared dev environments. It's practically free to have as many environments as you want since you only pay for what you use. Levarging lambda versioning.
* AWS services have different pricing models, we can think carefully about how we can play those off of each other to save costs. Lambda is the generic plug that fills gaps in AWS services, the core business logic, let the AWS services do everything else. Give the (AWS) platform the _usual_ server roles.
* AWS challenges the three tier architecture. S3, DDB and many others are available over HTTPS and AWS has good, fine grained security, that should allow us to let users talk directly to those resources - smart clients.
