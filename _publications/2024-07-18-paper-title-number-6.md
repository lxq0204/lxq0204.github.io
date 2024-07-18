---
title: "TextAdapter: Self-supervised Domain Adaptation for Cross-domain Text Recognition"
collection: publications
permalink: /publication/2024-05-24-paper-title-number-5
excerpt: 'This paper is about ....'
date: 2024-02-17
venue: ' IEEE Transactions on Multimedia'
paperurl: 'http://lxq0204.github.io/files/paper5.pdf'
citation: 'X. Liu, P. Zhang, X. Luo, Z. Huang, and X. Xu. (2024). &quot;TextAdapter: Self-supervised Domain Adaptation for Cross-domain Text Recognition.&quot; <i> IEEE Transactions on Multimedia</i>. DOI: 10.1109/TMM.2024.3400669.'
---

Text recognition remains challenging, primarily due to the scarcity of annotated real data or the hard labor to annotate large-scale real data. Most existing solutions rely on synthetic training data, where the synthetic-to-real domain gaps limit the model performance on real data. Unsupervised domain adaptation (UDA) methods have been proposed, aiming to obtain domain-invariant representations. However, they commonly focus on domain-level alignment, neglecting the fine-grained character features and thus leading to indistinguishable characters. In this paper, we propose a simple yet eective self-supervised UDA framework tailored for cross-domain text recognition, named TextAdapter, which integrates contrastive learning and consistency regularization to mitigate domain gaps. Specifically, a fine-grained feature alignment module based on character contrastive learning is designed to learn domain-invariant character representations by category-level alignment. Additionally, to address the task-agnostic problem in contrastive learning, i.e., ignoring the sequence semantics, an instance consistency matching module is proposed to perceive the contextual semantics by matching the prediction consistency among target data dierent augmented views. Experimental results on crossdomain benchmarks demonstrate the eectiveness of our method. Furthermore, TextAdapter can be embedded in most o-the-shelf text recognition models with new state-of-the-art performance, which illustrates the generality of our framework.

