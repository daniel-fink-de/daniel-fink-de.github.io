---
title: "Simulation stochastic processes with variational quantum circuits"
collection: theses
permalink: /publication/2022-02-22-simulating-stochastic-processes-with-variational-quantum-circuits
excerpt: 'This theses is my master theses.'
date: 2022-02-22
venue: 'OPUS - Publication Server of the University of Stuttgart'
paperurl: 'http://dx.doi.org/10.18419/opus-12068'
citation: 'Fink, Daniel. "Simulation stochastic processes with variational quantum circuits." Master's thesis, 2022. DOI: 10.18419/opus-12068'
---
**Abstract**

Simulating future outcomes based on past observations is a key task in predictive modeling and has found application in many areas ranging from neuroscience to the modeling of financial markets. The classical provably optimal models for stationary stochastic processes are so-called ϵ-machines, which have the structure of a unifilar hidden Markov model and offer a minimal set of internal states. However, these models are not optimal in the quantum setting, i.e., when the models have access to quantum devices. The methods proposed so far for quantum predictive models rely either on the knowledge of an ϵ-machine, or on learning a classical representation thereof, which is memory inefficient since it requires exponentially many resources in the Markov order. Meanwhile, variational quantum algorithms (VQAs) are a promising approach for using near-term quantum devices to tackle problems arising from many different areas in science and technology. Within this work, we propose a VQA for learning quantum predictive models directly from data on a quantum computer. The learning algorithm is inspired by recent developments in the area of implicit generative modeling, where a kernel-based two-sample-test, called maximum mean discrepancy (MMD), is used as a cost function. A major challenge of learning predictive models is to ensure that arbitrarily many time steps can be simulated accurately. For this purpose, we propose a quantum post-processing step that yields a regularization term for the cost function and penalizes models with a large set of internal states. As a proof of concept, we apply the algorithm to a stationary stochastic process and show that the regularization leads to a small set of internal states and a constantly good simulation performance over multiple future time steps, measured in the Kullback-Leibler divergence and the total variation distance.

[Download theses here](https://elib.uni-stuttgart.de/bitstream/11682/12085/1/2022_02_22_Master_Thesis_Daniel_Fink.pdf)

Fink, Daniel. "Simulation stochastic processes with variational quantum circuits." Master's thesis, 2022. DOI: 10.18419/opus-12068