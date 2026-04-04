---
title: "[Preprint] Reliable Control-Point Selection for Steering Reasoning in Large Language Models"
excerpt: "**Haomin Zhuang**, Hojun Yoo, Xiaonan Luo, Kehan Guo, Xiangliang Zhang <br/><img src='/images/stability-steering-concept.png'>"
collection: portfolio
date: 2026-04-02
---

Steering vectors can control reasoning behaviors in LLMs without retraining, but current methods detect behavioral boundaries through keyword matching—treating every match as genuine. We find that 93.3% of keyword-detected boundaries are behaviorally unstable. Our method, stability filtering, retains only boundaries where the model consistently reproduces the behavior, achieving 0.784 accuracy on MATH-500 (+5.0 over SEAL) with cross-model transfer.

<img src="/images/stability-steering-concept.png" width="100%"/>

Paper: [[arXiv](https://arxiv.org/abs/2604.02113)] | Code: [[GitHub](https://github.com/zhmzm/stability-steering)].
