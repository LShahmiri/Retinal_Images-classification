# Retinal_Images-classification
Retinal Disease Classification using Xception (Transfer Learning)

This project trains a deep learning model using Xception (ImageNet pretrained) to classify retinal fundus images into three categories:

Diabetic

Glaucoma

Heal (Healthy)

---------
Model Overview

Base model: Xception (pretrained on ImageNet)

Input size: 299×299 RGB

Augmentation: Random flip, rotation, zoom, contrast

Optimizer: Adam

Loss: Categorical Cross-Entropy

Metrics: Accuracy, AUC

Regularization: Dropout (0.3)

Fine-tuning: Unfreezes last 40 layers for domain adaptation
Model Evaluation

The script prints:

Precision, Recall, F1-score per class

Confusion matrix visualization

Weighted averages of all metrics
