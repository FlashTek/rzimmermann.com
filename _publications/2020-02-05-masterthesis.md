---
title: "Robust Perception in Humans and Machines"
type: thesis
collection: publications
permalink: /publication/2020-02-05-masterthesis
excerpt: 'Analyzing the robustness of computer vision and comparing it to human performance by developing novel evaluation methods'
date: 2017-08-02
paperurl: 'https://rzimmermann.com/files/Masters_Thesis_Roland_S_Zimmermann.pdf'
paperurldescription: 'Access the thesis'
authors: '**Zimmermann, R. S.**'
venue: 'University of Göttingen/University of Tübingen'
citation: 'Zimmermann, Roland S. (2020). Robust Perception in Humans and Machines.'
---
Under optimal conditions, modern computer vision algorithms based on neural networks can provide almost perfect performance on various perceptual tasks, such as image classification. However, these classifiers are often not robust and their performance deteriorates severely when faced with corrupted input images. Research on the robustness of image classifiers focuses on two types of image corruptions:
adversarial examples and common corruptions. While the former are image perturbations created by an adversary to cause wrong behavior of the algorithm, the latter describe image distortions that naturally occur outside of perfect lab conditions. In this work, new methods to evaluate the robustness of image classifiers against both types of corruption as well as approaches to increase the robustness are presented.

In a first step, the robustness of a defense strategy against adversarial perturbations, based on Bayesian neural networks and adversarial training, is analyzed. It is shown that by adjusting an existing adversarial attack to this defense, the defense
becomes ineffective.

Next, two methods are derived to assess the robustness of arbitrary image classifiers against image corruptions. This is motivated by the goal of performing a fair comparison between current image classification networks and human visual perception in terms of their robustness. The first method is a decision-based adversarial attack and searches image-dependent adversarial perturbations using Markov Chain
Monte Carlo sampling. It can be implemented using a two-alternatives-forced-choice task in a psychophysical experiment. The attack reaches competitive results compared to previous white-box attacks. In the second method, an image-independent
and dataset-dependent noise distribution is learned by an adversarial noise generator. The experiments indicate that image classifiers based on convolutional neural networks are more susceptible to this noise than to various other distributions such as Gaussian noise.

Finally, it is demonstrated that the robustness of a common image classification network (ResNet-50) against common corruptions can be improved strongly
by using a simple but properly tuned Gaussian data augmentation. This simple baseline easily reaches previous state-of-the-art performance on the popular corruption benchmark ImageNet-C. Built upon this strong baseline and the previously proposed adversarial noise generator, it is shown that an adversarial training of the recognition model against uncorrelated worst-case noise distributions leads to an additional increase in performance.

[Download thesis here](https://rzimmermann.com/files/Masters_Thesis_Roland_S_Zimmermann.pdf)
