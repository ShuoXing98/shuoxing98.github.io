---
title:          "A Threshold Greedy Algorithm for Noisy Submodular Maximization"
date:           2023-12-05 00:01:00 +0800
selected:       false
# pub:            "arXiv"
pub_post:       'Under review.'
pub_date:       "2023"
abstract: >-
  We address the problem of submodular maximization where objective function $f:2^U\to\mathbb{R}_{\geq 0}$ can only be accessed through i.i.d noisy queries. This problem arises in many applications including influence maximization, diverse recommendation systems, and large-scale facility location optimization. We propose an efficient adaptive sampling strategy, called \samplong (\samp), that is inspired by algorithms for best-arm-identification in multi-armed bandit, which significantly improves sample efficiency. We integrate \samp into existing approximation algorithms for submodular maximization, resulting in algorithms with approximation guarantees arbitrarily close to the standard value oracle setting that are highly sample-efficient. We propose and analyze sample-efficient algorithms for monotone submodular maximization with cardinality and matroid constraints, as well as unconstrained non-monotone submodular maximization. Our theoretical analysis is complemented by empirical evaluation on real instances, demonstrating the superior sample efficiency of our proposed algorithm relative to alternative approaches.
# cover:          /assets/images/covers/cover1.jpg
authors:
- Wenjing Chen
- Shuo Xing
- Victoria G. Crawford
links:
  Paper: https://arxiv.org/abs/2312.00155
---
