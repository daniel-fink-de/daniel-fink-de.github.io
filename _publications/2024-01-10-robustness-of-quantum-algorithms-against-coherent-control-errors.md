---
title: "Robustness of quantum algorithms against coherent control errors"
collection: publications
permalink: /publication/2024-01-10-robustness-of-quantum-algorithms-against-coherent-control-errors
excerpt: ''
date: 2024-01-10
venue: 'Phys. Rev. A'
paperurl: 'https://doi.org/10.1103/PhysRevA.109.012417'
citation: 'Julian Berberich, Daniel Fink and Christian Holm. &quot;Robustness of quantum algorithms against coherent control errors.&quot; Phys. Rev. A, Jan. 2024. DOI:'
---
**Abstract:** Coherent control errors, for which ideal Hamiltonians are perturbed by unknown multiplicative noise terms, are a major obstacle for reliable quantum computing. In this paper, we present a framework for analyzing the robustness of quantum algorithms against coherent control errors using Lipschitz bounds. We derive worst-case fidelity bounds which show that the resilience against coherent control errors is mainly influenced by the norms of the Hamiltonians generating the individual gates. These bounds are explicitly computable even for large circuits, and they can be used to guarantee fault-tolerance via threshold theorems. Moreover, we apply our theoretical framework to derive a novel guideline for robust quantum algorithm design and transpilation, which amounts to reducing the norms of the Hamiltonians. Using the 3-qubit Quantum Fourier Transform as an example application, we demonstrate that this guideline targets robustness more effectively than existing ones based on circuit depth or gate count. Furthermore, we apply our framework to study the effect of parameter regularization in variational quantum algorithms. The practicality of the theoretical results is demonstrated via implementations in simulation and on a quantum computer.