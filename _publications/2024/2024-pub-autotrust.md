---
title:          "AutoTrust: Benchmarking Trustworthiness in Large Vision Language Models for Autonomous Driving"
date:           2024-12-19 00:08:00 +0800
selected:       true
# pub:            "Findings of the Association for Computational Linguistics (ACL Findings)"
# pub_pre:        "Submitted to "
pub_post:       'Under review.'
pub_last:       '<a href="https://github.com/taco-group/AutoTrust" target="_blank"><img src="https://img.shields.io/github/stars/taco-group/AutoTrust"></a>'
pub_date:       "2024"

abstract: >-
  We constructed the largest visual question-answering dataset for investigating trustworthiness issues in driving scenarios, comprising over 10k unique scenes and 18k queries. We evaluated six publicly available VLMs, spanning from generalist to specialist, from open-source to commercial models. Our exhaustive evaluations have unveiled previously undiscovered vulnerabilities of DriveVLMs to trustworthiness threats. Specifically, we found that the general VLMs like LLaVA-v1.6 and GPT-4o-mini surprisingly outperform specialized models fine-tuned for driving in terms of overall trustworthiness. DriveVLMs like DriveLM-Agent are particularly vulnerable to disclosing sensitive information. Additionally, both generalist and specialist VLMs remain susceptible to adversarial attacks and struggle to ensure unbiased decision-making across diverse environments and populations. Our findings call for immediate and decisive action to address the trustworthiness of DriveVLMs -- an issue of critical importance to public safety and the welfare of all citizens relying on autonomous transportation systems.
cover:          /assets/images/covers/autotrust-teaser.png
authors:
  - Shuo Xing
  - Hongyuan Hua
  - Xiangbo Gao
  - Shenzhe Zhu
  - Renjie Li
  - Kexin Tian
  - Xiaopeng Li
  - Heng Huang
  - Tianbao Yang
  - Zhangyang Wang
  - Yang Zhou
  - Huaxiu Yao
  - Zhengzhong Tu
links:
  Paper: https://arxiv.org/abs/2412.15206
  Code: https://github.com/taco-group/AutoTrust
  Website: https://taco-group.github.io/AutoTrust/
---
