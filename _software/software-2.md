---
title: "NIMIWAE"
excerpt: "Non-Ignorably Missing Importance-Weighted Autoencoder"
collection: software
---

[NIMIWAE](https://github.com/DavidKLim/NIMIWAE) performs imputation of missing data. Specifically, it is able to handle any mechanism of missing data, including the difficult Missing Not At Random (MNAR) case. By utilizing neural networks, NIMIWAE can learn complex dependencies across features of potentially high-dimensional datasets. Additionally, NIMIWAE uses a neural network to model the missingness mechanism, which can be adapted to account for any Missing Completely at Random (MCAR), Missing at Random (MAR), or MNAR missingness. By increasing the complexity of the missingness neural network, potentially complex dependencies between the missingness of the features can also be captured.

<br/><img src='/images/NIMIWAE_architecture.png'>