---
layout: post
title:  "Acceptance Testing"
tags: testing
summary: The acceptance tests are what not how.
---

[Acceptance Testing - Webinar](https://courses.cd.training)

## My Take Aways

1. We want to assert on what the users of our system want of it.
2. If we can write the automated test first, then we have an automated definition of done.
3. Really we want an executable specification, written by anyone, owned by developers.
4. End-to-end testing has some drawbacks that make it an anti-pattern, instead we should just test our system, and test the contracts between the systems. Tests should be shared between the upstream and downstream teams on those contracts.
5. The test infrastructure can hide complexity to make sure that tests are isolated.
6. 4 Layers: Test Case -> DSL -> Protocol Driver -> System Under Test.
