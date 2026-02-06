---
title: "Latency and Backlog Bounds in Time-Sensitive Networking with Credit Based Shapers and Asynchronous Traffic Shaping"
collection: publications
category: conferences
permalink: /publication/2019-09-03-latency-backlog-bounds
excerpt: ''
date: 2019-09-03
venue: '30th International Teletraffic Congress (ITC 30)'
paperurl: 'https://academicpages.github.io/files/paper3.pdf'
citation: 'E. Mohammadpour, E. Stai, M. Mohiuddin and J. -Y. Le Boudec, "Latency and Backlog Bounds in Time-Sensitive Networking with Credit Based Shapers and Asynchronous Traffic Shaping," 2018 30th International Teletraffic Congress (ITC 30), Vienna, Austria, 2018, pp. 1-6, doi: [10.1109/ITC30.2018.10053](https://doi.org/10.1109/ITC30.2018.10053).'
---

We compute bounds on end-to-end worst-case latency and on nodal backlog size for a per-class deterministic network that implements Credit Based Shaper (CBS) and Asynchronous Traffic Shaping (ATS), as proposed by the Time-Sensitive Networking (TSN) standardization group. ATS is an implementation of the Interleaved Regulator, which reshapes traffic in the network before admitting it into a CBS buffer, thus avoiding burstiness cascades. Due to the interleaved regulator, traffic is reshaped at every switch, which allows for the computation of explicit delay and backlog bounds. Furthermore, we obtain a novel, tight per-flow bound for the response time of CBS, when the input is regulated, which is smaller than existing network calculus bounds. We also compute a per-flow bound on the response time of the interleaved regulator. Based on all the above results, we compute bounds on the per-class backlogs. Then, we use the newly computed delay bounds along with recent results on interleaved regulators from literature to derive tight end-to-end latency bounds and show that these are less than the sums of per-switch delay bounds.
