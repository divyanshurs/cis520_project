# Study-of-Generative-Models
The project aims to compare different generative models, that utilizes encoder-decoder architectures. In this study, we fit three different models - Principal component analysis, Autoencoders and Variational autoencoders- on CIFAR 10 dataset. We perturb their latent space in three ways, and compare the image generated. During the course of the study, we found that autoencoders were able to generate a few synthetic images that were visually believable. The study concludes by comparing these models by passing the synthetic image generated through a pretrained Alexnet built for CIFAR 10 classification, and proves that the autoencoders are better in generating better synthetic images than that of PCA and the baseline

You can download the pretrained weights at - https://drive.google.com/drive/folders/1mOYjWp33dyCJ594tMfcFQ2fwX8ZHMU7z

The final project report which summarises our results and findings can be accessed [here](/Study_of_Generative_Models.pdf).
