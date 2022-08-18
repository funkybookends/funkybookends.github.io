---
layout: post
title:  "How NOT to Measure Latency"
tags: metrics
summary: Document, delegate, and communicate to reduce the circus factor in your team.
---

["How NOT to Measure Latency" by Gil Tene](https://www.youtube.com/watch?v=lJ8ydIuPFeU)

## My Take Aways

We are trying to find the best way to describe multiple events each with their latency

1. The 95th percentile, it is hiding the 5% worst latencies. It's very easy to hide the worst data, you need to plot the max.
2. You cannot average an average and end up with a meaningful number, so don't average percentiles.
3. The chance of having the 99pc expeirience in your metrics is much more likely than you think.
4. When load testing, it's important to measure the time the client sees,mresponse time, not the time that was measured inside the code, service time,l as that omits the time a user spends in "an HTTP queue" which is relevant.
5. Throughput is hard to measure. Really there is a performance drop off as throughput increases, so it's not about "how much can it handle", it's about how does it degrade as throughput increases. From there you can decide your acceptable level of degredation, and make a decision based on that.
