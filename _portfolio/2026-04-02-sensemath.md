---
title: "SenseMath: When Number Sense Helps Numerical Reasoning in Large Language Models"
excerpt: "**Haomin Zhuang**, Xiangqi Wang, Yili Shen, Ying Cheng, Xiangliang Zhang <br/><img src='/images/sensemath_overview.png'>"
collection: portfolio
date: 2026-04-02
---

Large language models often default to step-by-step computation even when efficient numerical shortcuts are available. We introduce **SenseMath**, a controlled benchmark for evaluating structure-sensitive numerical reasoning in LLMs. SenseMath contains 4,800 items spanning eight shortcut categories and four digit scales, with matched strong-shortcut, weak-shortcut, and control variants. It supports three evaluation settings of increasing cognitive demand: *Shortcut Use* (whether models can apply shortcuts), *Applicability Judgment* (whether they can recognize when a shortcut is appropriate), and *Problem Generation* (whether they can generate new shortcut-amenable problems).

Our evaluation across five LLMs shows that when explicitly prompted, models readily adopt shortcut strategies and achieve substantial accuracy gains on shortcut-amenable items (up to 15%), yet under standard chain-of-thought prompting they spontaneously employ such strategies in fewer than 40% of cases. Moreover, models systematically over-generalise shortcuts to problems where they do not apply, and fail to generate valid shortcut-bearing problems from scratch. These results suggest that current LLMs exhibit *procedural* shortcut fluency without the *structural* understanding that underlies human number sense.

[[Project Page](https://zhmzm.github.io/SenseMath/)] [[Code](https://github.com/zhmzm/SenseMath)] [[Dataset](https://huggingface.co/datasets/DaydreamerMZM/SenseMath)]

<br/><img src='/images/sensemath_results.png'>
