---
title:          "DecAlign: Hierarchical Cross-Modal Alignment for Decoupled Multimodal Representation Learning"
date:           2026-01-25 23:01:00 +0800
selected:       false
pub:            "The Fourteenth International Conference on Learning Representations (ICLR)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       '<a href="https://github.com/taco-group/DecAlign" target="_blank"><img src="https://img.shields.io/github/stars/taco-group/DecAlign"></a>'
pub_date:       "2026"

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
  OpenReview: https://openreview.net/forum?id=LasUPe2UxG
  Code: https://github.com/taco-group/DecAlign
  Website: https://taco-group.github.io/DecAlign/
---
