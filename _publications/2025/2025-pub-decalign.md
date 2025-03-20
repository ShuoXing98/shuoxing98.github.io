---
title:          "DecAlign: Hierarchical Cross-Modal Alignment for Decoupled Multimodal Representation Learning"
date:           2025-03-14 23:01:00 +0800
selected:       false
# pub:            "The 3rd WACV Workshop on Large Language and Vision Models for Autonomous Driving (LLVM-AD)"
# pub_pre:        "Submitted to "
pub_post:       'Under review.'
pub_date:       "2025"

abstract: >-
  We introduce DecAlign, a novel hierarchical cross-modal alignment framework designed to decouple multimodal representations into modality-unique (heterogeneous) and modality-common (homogeneous) features. For handling heterogeneity, we employ a prototype-guided optimal transport alignment strategy leveraging gaussian mixture modeling and multi-marginal transport plans, thus mitigating distribution discrepancies while preserving modality-unique characteristics. To reinforce homogeneity, we ensure semantic consistency across modalities by aligning latent distribution matching with Maximum Mean Discrepancy regularization. Furthermore, we incorporate a multimodal transformer to enhance high-level semantic feature fusion, thereby further reducing cross-modal inconsistencies. Our extensive experiments on four widely used multimodal benchmarks demonstrate that DecAlign consistently outperforms existing state-of-the-art methods across five metrics.
cover:          /assets/images/covers/decalign_pip.png
authors:
  - Chengxuan Qian
  - Shuo Xing
  - Shawn Li
  - Yue Zhao
  - Zhengzhong Tu
links:
  Paper: https://arxiv.org/abs/2503.11892
  Code: https://github.com/taco-group/DecAlign
  Website: https://taco-group.github.io/DecAlign/
---
