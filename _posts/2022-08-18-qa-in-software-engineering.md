---
layout: post
title:  "Role of QA in Software Engineering"
tags: "QA"
summary: QA are not a gatekeeper, quality should be built in and feedback fast.
---

[Quality Assurance in Agile Software](https://www.youtube.com/watch?v=XhFVtuNDAoM)

## My Take Aways

1. QA should not be gatekeepers to production
2. Quality must be built into the product - not inspected. This is done by adding tests as part of the development process and ensuring they are run as part of the deployment process.
3. Fast feedback is really important. Developers need to know as soon as possible about an issue, and the tests run as frequently as possible so that it's easy to identify the source of the problem. TDD is one of the fastest ways to get this kind of feedback.
4. High quality comes from working in small fast definitive steps where quality is monitiored after each step.
5. Removing QA as a gatekeeper and building it into the prior steps is not actually disregarding quality, it's bringing it front and center.
6. The developers need to be the ones responsible for all the automated tests, as they are the ones that will cause the tests to fail and therfore need to be able to run them, debug them and maintain them.
7. Manual tests have their place, but it should only be on the bleeding edge of new features. Humans shouldn't check so much "does it work?" but instead should be checking, does it work well, does it meet their needs, i.e. more subjective explorations.
