---
title: "Reliable Control-Point Selection for Steering Reasoning in Large Language Models"
collection: publications
permalink: /publication/2026-04-02-stability-steering
excerpt: 'We find that 93.3% of keyword-detected reasoning boundaries are behaviorally unstable. Our stability filtering method retains only genuine behavioral signals, achieving 0.784 accuracy on MATH-500 (+5.0 over SEAL) with cross-model transfer.'
date: 2026-04-02
venue: 'arXiv'
paperurl: 'https://github.com/zhmzm/stability-steering'
citation: 'Haomin Zhuang, Hojun Yoo, Xiaonan Luo, Kehan Guo, Xiangliang Zhang. (2026). &quot;Reliable Control-Point Selection for Steering Reasoning in Large Language Models.&quot; <i>arXiv preprint</i>.'
---

Steering vectors offer a training-free way to control reasoning behaviors in LLMs, but existing methods detect behavioral boundaries through keyword matching—treating every match as a genuine signal. We find that **93.3% of keyword-detected boundaries are behaviorally unstable**: the model fails to reproduce the detected behavior when re-run from the same prefix. We develop a probabilistic model of intrinsic reasoning behaviors and propose **stability filtering**, which retains only high-probability boundaries. Combined with content-subspace projection, this achieves **0.784** accuracy on MATH-500 (+5.0 over SEAL), and the vectors transfer across models without re-extraction.

![Concept Figure](/images/stability-steering-concept.png)

[Code](https://github.com/zhmzm/stability-steering)

Recommended citation: Haomin Zhuang, Hojun Yoo, Xiaonan Luo, Kehan Guo, Xiangliang Zhang. (2026). "Reliable Control-Point Selection for Steering Reasoning in Large Language Models." <i>arXiv preprint</i>.
