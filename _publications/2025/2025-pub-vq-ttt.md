---
title:          "Demystifying the Visual Quality Paradox in Multimodal Large Language Models"
date:           2025-06-22 23:01:00 +0800
selected:       false
# pub:            "The 3rd WACV Workshop on Large Language and Vision Models for Autonomous Driving (LLVM-AD)"
# pub_pre:        "Submitted to "
pub_post:       'Under review.'
pub_date:       "2025"

abstract: >-
  We conduct the first systematic study spanning leading MLLMs and a suite of vision-language benchmarks, applying controlled degradations and stylistic shifts to each image. Surprisingly, we uncover a visual-quality paradox: model, task, and even individual-instance performance can improve when images deviate from human-perceived fidelity. Off-the-shelf restoration pipelines fail to reconcile these idiosyncratic preferences. To close the gap, we introduce Visual-Quality Test-Time Tuning (VQ-TTT)-a lightweight adaptation module that: (1) inserts a learnable, low-rank kernel before the frozen vision encoder to modulate frequency content; and (2) fine-tunes only shallow vision-encoder layers via LoRA. 
cover:          /assets/images/covers/vq-ttt.png
authors:
  - Shuo Xing*
  - Lanqing Guo*
  - Hongyuan Hua*
  - Seoyoung Lee
  - Peiran Li
  - Yufei Wang
  - Zhangyang Wang
  - Zhengzhong Tu
links:
  Paper: https://arxiv.org/abs/2506.15645
---
