---
title: "[ICLR'24] Backdoor Federated Learning by Poisoning Backdoor-Critical Layers"
excerpt: "**Haomin Zhuang**, Mingxian Yu, Hao Wang, Yang Hua, Jian Li, Xu Yuan <br/><img src='/images/lsa.jpg'>"
collection: portfolio
---

Federated learning (FL) has been widely deployed to enable machine learning training on sensitive data across distributed devices. However, the decentralized learning paradigm and heterogeneity of FL further extend the attack surface for backdoor attacks. Existing FL attack and defense methodologies typically focus on the whole model. None of them recognizes the existence of backdoor-critical (BC) layers - a small subset of layers that dominate the model vulnerabilities. Attacking the BC layers achieves equivalent effects as attacking the whole model but at a far smaller chance of being detected by state-of-the-art (SOTA) defenses. This paper proposes a general in-situ approach that identifies and verifies BC layers from the perspective of attackers. Based on the identified BC layers, we carefully craft a new backdoor attack methodology that adaptively seeks a fundamental balance between attacking effects and stealthiness under various defense strategies. Extensive experiments show that our BC layer-aware backdoor attacks can successfully backdoor FL under seven SOTA defenses with only 10% malicious clients and outperform latest backdoor attack methods.

This paper is accepted by [ICLR'24](https://iclr.cc/) [[Paper](https://openreview.net/pdf?id=AJBGSVSTT2)]. Code is available in [Github](https://github.com/zhmzm/Poisoning_Backdoor-critical_Layers_Attack).

<br/><img src='/images/lsa.jpg'>
