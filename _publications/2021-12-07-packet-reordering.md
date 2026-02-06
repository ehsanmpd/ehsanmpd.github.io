---
title: "On packet reordering in time-sensitive networks"
collection: publications
category: manuscripts
permalink: /publication/2021-12-07-packet-reordering
excerpt: ''
date: 2021-12-07
venue: 'IEEE/ACM Transactions on Networking'
slidesurl: 'https://ieeexplore.ieee.org/abstract/document/9640523'
paperurl: 'https://arxiv.org/pdf/2008.03075'
bibtexurl: 'https://ehsanmpd.github.io/files/packet-reordering.bib'
citation: 'E. Mohammadpour and J. -Y. Le Boudec, "On Packet Reordering in Time-Sensitive Networks," in IEEE/ACM Transactions on Networking, vol. 30, no. 3, pp. 1045-1057, June 2022, doi: 10.1109/TNET.2021.3129590.'
---

Time-sensitive networks (IEEE TSN or IETF DetNet) may tolerate some packet reordering. Re-sequencing buffers are then used to provide in-order delivery, the parameters of which (timeout, buffer size) may affect worst-case delay and delay jitter. There is so far no precise understanding of per-flow reordering metrics nor of the dimensioning of re-sequencing buffers in order to provide worst-case guarantees, as required in such networks. First, we show that a previously proposed per-flow metric, reordering late time offset (RTO), determines the timeout value. If the network is lossless, another previously defined metric, the reordering byte offset (RBO), determines the required buffer. If packet losses cannot be ignored, the required buffer may be larger than RBO, and depends on jitter, an arrival curve of the flow at its source, and the timeout. Then we develop a calculus to compute the RTO for a flow path; the method uses a novel relation with jitter and arrival curve, together with a decomposition of the path into non order-preserving and order-preserving elements. We also analyse the effect of re-sequencing buffers on worst-case delay, jitter and propagation of arrival curves. We show in particular that, in a lossless (but non order-preserving) network, re-sequencing is “for free”, namely, it does not increase worst-case delay nor jitter, whereas in a lossy network, re-sequencing increases the worst-case delay and jitter. We apply the analysis to evaluate the performance impact of placing re-sequencing buffers at intermediate points and illustrate the results on two industrial test cases.
