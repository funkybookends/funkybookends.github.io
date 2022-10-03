---
layout: post
title:  "How to A/B test with Confidence"
tags: testing
summary: "A/B testing is mostly in the setup"
---

[How to A/B test with confidence - Frederick Cheung](https://www.youtube.com/watch?v=IsgQ9RJ0rJE)

## My Take Aways

1. A/B testing can be used for lots of things, not just layouts designs or flows, but also algorithms for example.
2. The statistical test depends on the type of metric. Be careful to get the maths right.
3. Be wary of short experiments. Real life things can complicate the results.
4. Bayesian approach might be more powerful if you have lower base rates as you can incorporate existing knowledge.
5. Be careful how you randomize, and how you randomize between tests. You don't want one user who is constantly getting experimented on. If you can prove that before the test, the groups are equivalent, that can be helpful.
6. Split users into your two groups as late as possible.
7. You need to take a scientific approach, and agree the test set-up, methods, and analysis prior to implementing the test, otherwise you'll be P-hacking, and choosing your results.
8. Be aware of compounding factors. If a flow is less reliable and has more crashes, that is part of the test weather you like it or not.
9. Be aware of outliers that can skew the statistics.
10. Understand the domain, perhaps there is a lag that is relevant, or other domain knowledge that might impact the design or interpretation.
11. Result splitting is another pitfall to find the result you want.
12. Practice with an A/A test.
13. Don't over test, it's not a substitue for talking with your customers.
