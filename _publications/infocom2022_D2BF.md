---
title: "D$$^2$$BF---Data-Driven Beamforming in MU-MIMO with Channel Estimation Uncertainty"
collection: publications
date: 2022-05-02
excerpt: ''
venue: 'IEEE INFOCOM'
permalink: /publications/infocom2022_D2BF
paperurl: 
citation:
---
**Abstract**: Accurate estimation of Channel State Information (CSI) is essential to design MU-MIMO beamforming. However, errors in CSI estimation are inevitable in practice. State-of-the-art works model CSI as random variables and assume certain specific distributions or worst-case boundaries, both of which suffer performance issues when providing performance guarantees to the users. In contrast, this paper proposes a Data-Driven Beamforming (D$$^2$$BF) that directly handles the available CSI data samples (without assuming any particular distributions). Specifically, we employ chance-constrained programming (CCP) to provide probabilistic data rate guarantees to the users and introduce $$\infty$$-Wasserstein ambiguity set to bridge the unknown CSI distribution with the available (limited) data samples. Through problem decomposition and a novel bilevel formulation for each subproblem, we show that each subproblem can be solved by binary search and convex approximation. We also validate that D$$^2$$BF offers better performance than the state-of-the-art approach while meeting probabilistic data rate guarantees to the users.

[Read more](https://ieeexplore.ieee.org/abstract/document/9796930)
