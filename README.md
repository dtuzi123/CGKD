
# Lifelong Variational Autoencoder via Online Adversarial Expansion Strategy

>📋 This is the implementation of Continual Variational Autoencoder via Continual Generative Knowledge

>📋 Accepted by AAAI 2023 (Oral)

# Title : Continual Variational Autoencoder via Continual Generative Knowledge

# Paper link : 


# Abstract
Humans and other living beings have the ability of short and long-term memorization during their entire lifespan. However, most existing Continual Learning (CL) methods can only account for short-term information when training on infinite streams of data. In this paper, we develop a new unsupervised continual learning framework consisting of two memory systems using Variational Autoencoders (VAEs). We develop a Short-Term Memory (STM), and a parameterised scalable memory implemented by a Teacher model aiming to preserve the long-term information. To incrementally enrich the Teacher's knowledge during training, we propose the Knowledge Incremental Assimilation Mechanism (KIAM), which evaluates the knowledge similarity between the STM and the already accumulated information as signals to expand the Teacher's capacity. Then we train a VAE as a Student module and propose a new Knowledge Distillation (KD) approach that gradually transfers generative knowledge from the Teacher to the Student module. To ensure the quality and diversity of knowledge in KD, we propose a new expert pruning approach that selectively removes the Teacher's redundant parameters, associated with certain unnecessary experts that have preserved the knowledge corresponding to overlapping probabilistic representations. This mechanism further reduces the complexity of the Teacher's module while ensuring the diversity of knowledge for the KD procedure. We show theoretically and empirically that the proposed framework can train a statistically diversified Teacher module for continual VAE learning which is applicable to infinite data streams.

# Environment

1. Tensorflow 2.1
2. Python 3.6

# Training and evaluation

>📋 Python xxx.py, the model will be automatically trained and then report the results after the training.

>📋 Different parameter settings of OCM would lead different results and we also provide different settings used in our experiments.

# BibTex
>📋 If you use our code, please cite our paper as:


