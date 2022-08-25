---
title: "Paper: Backdoor Federated Learning by Poisoning Backdoor-critical Layers (Under Review)"
excerpt: "This paper proposes a novel method to recognize backdoor-critical layers and a attack strategy to backdoor Federated Learning. <br/><img src='/images/LPA.png'>"
collection: portfolio
---

Abstract: Backdoor attacks inject adversarial triggers to training data samples that induce machine learning models to make targeted incorrect predictions on testing data with the trigger embedded. The decentralized learning paradigm and heterogeneity of federated learning (FL) further extend the attack surface for backdoor attacks. A few backdoor attack and defense methodologies have been proposed for FL. However, none of them recognizes that poisoning backdoor-critical (BC) layers—a small set of model layers—rather than the whole model can successfully backdoor FL at a minimum
chance of being detected by state-of-the-art (SOTA) defenses. In this work, we first propose to use forward and backward layer substitution to identify backdoor-critical layers and analyze their properties. Then, we craft new backdoor attack methods with the awareness of BC layers. Extensive experiments show that our BC layer-aware backdoor attacks can successfully backdoor FL under SOTA defense methods with only 10% malicious clients and maintain the main task accuracy at a high level.

This paper is under review in a Conference.
<br/><img src='/images/LPA.png'>
