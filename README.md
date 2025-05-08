# Cognition-Computation
Robust Image Classification with DBNs and CNNs

This project explores image classification through the lens of visual concept learning, comparing two deep learning architectures: Deep Belief Networks (DBNs) and Convolutional Neural Networks (CNNs). Implemented in Python with PyTorch, the study not only evaluates classification performance on the Fashion MNIST dataset but also focuses on robustness under noise and adversarial conditions.

While CNNs achieve higher accuracy and faster training in clean settings, DBNs exhibit superior resilience in non-ideal scenarios. Specifically, DBNs sustain stronger performance when exposed to noisy inputs or adversarial attacks—likely due to their probabilistic, generative structure and ability to model complex data distributions.

Experiments further show that DBN architecture depth matters: a two-layer DBN consistently outperforms both shallower and deeper variants, underscoring the need for appropriate model complexity.

Ultimately, this work highlights that test accuracy alone isn't enough. In real-world applications, robustness is equally vital. DBNs, with their stability under perturbation, emerge as a reliable alternative for environments where input integrity can't be guaranteed.


