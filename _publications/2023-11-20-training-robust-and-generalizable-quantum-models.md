---
title: "Training robust and generalizable quantum models"
collection: publications
permalink: /publication/2023-11-20-training-robust-and-generalizable-quantum-models
excerpt: ''
date: 2023-11-20
venue: 'arXiv'
paperurl: 'https://doi.org/10.48550/arXiv.2311.1187'
citation: 'Berberich, Julian, Daniel Fink, Daniel Pranjić, Christian Tutschku, and Christian Holm. &quot;Training robust and generalizable quantum models.&quot; preprint, 2023. DOI:'
---
**Abstract:** Adversarial robustness and generalization are both crucial properties of reliable machine learning models. In this paper, we study these properties in the context of quantum machine learning based on Lipschitz bounds. We derive tailored, parameter-dependent Lipschitz bounds for quantum models with trainable encoding, showing that the norm of the data encoding has a crucial impact on the robustness against perturbations in the input data. Further, we derive a bound on the generalization error which explicitly depends on the parameters of the data encoding. Our theoretical findings give rise to a practical strategy for training robust and generalizable quantum models by regularizing the Lipschitz bound in the cost. Further, we show that, for fixed and non-trainable encodings as frequently employed in quantum machine learning, the Lipschitz bound cannot be influenced by tuning the parameters. Thus, trainable encodings are crucial for systematically adapting robustness and generalization during training. With numerical results, we demonstrate that, indeed, Lipschitz bound regularization leads to substantially more robust and generalizable quantum models.