---
title:          "LLMs Can Get \"Brain Rot\"!"
date:           2025-10-17 00:08:00 +0800
selected:       true
# pub:            "Findings of the Association for Computational Linguistics (ACL Findings)"
# pub_pre:        "Submitted to "
pub_post:       'Under review.'
# pub_last:       '<a href="https://github.com/taco-group/AutoTrust" target="_blank"><img src="https://img.shields.io/github/stars/taco-group/AutoTrust"></a>'
pub_date:       "2025"

abstract: >-
  We propose and test the LLM Brain Rot Hypothesis: continual exposure to junk web text causes lasting cognitive decline in large language models. Using real Twitter/X corpora, we build matched junk and control datasets along two orthogonal dimensions—M1 (engagement) and M2 (semantic quality)—and continually pre-train four LLMs. Junk-fed models show clear deterioration (Hedges’ g > 0.3) in reasoning, long-context understanding, safety, and personality alignment. Performance decays with increasing junk ratio (e.g., ARC-CoT 74.9 → 57.2, RULER-CWE 84.4 → 52.3). Forensics reveal: (1) Thought-skipping as the core lesion; (2) Partial, irreversible recovery despite further tuning; and (3) Popularity, not text length, as the strongest predictor of “brain rot.”
cover:          /assets/images/covers/llm-brain-rot-teaser.png
authors:
  - Shuo Xing*
  - Junyuan Hong*#
  - Yifan Wang
  - Runjin Chen
  - Zhenyu Zhang
  - Ananth Grama
  - Zhengzhong Tu
  - Zhangyang Wang#
links:
  Paper: https://arxiv.org/abs/2510.13928
  Code: https://github.com/llm-brain-rot/llm-brain-rot
  Website: https://llm-brain-rot.github.io/
---
