# Siamese network

A Siamese network is a type of artificial neural network architecture that uses two or more identical subnetworks, sharing the same weights, to compare two different inputs and determine their similarity.

Siamese networks have become a common structure in various recent models for unsupervised visual representation learning. These models maximize the similarity between two augmentations of one image, subject to certain conditions for avoiding collapsing solutions.

Siamese networks can learn meaningful representations without using any of the following:<br>
(i) negative sample pairs,<br>
(ii) large batches,<br>
(iii) momentum encoders.<br>

Experiments with Siamese networks show that collapsing solutions do exist for the loss and structure, but a stop-gradient operation plays an essential role in preventing collapse. It provides a hypothesis on the implications of stop-gradient, and further shows proof-of-concept experiments verifying it. Our “SimSiam” method achieves competitive results on ImageNet and downstream tasks. This work motivates people to rethink the roles of Siamese architectures in unsupervised representation learning.
