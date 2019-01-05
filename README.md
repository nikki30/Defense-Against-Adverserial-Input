# DefenseAgainstAdverserialInput
Study of Adversarial Attack and Defense Methods

## Introduction

Neural network is vulnerable to adversarial examples, which means that inputs formed by adding small perturbations will make network output incorrect answer with high confidence. Difficult to apply neural networks in security-critical area.

## Basic Setup

Dataset: Digit-recognition task (0-9) standard dataset MNIST
Network Structure: shown on the right
Our defense method focuses on the CW attack algorithm

![cnn](https://github.com/nikki30/Defense-Against-Adverserial-Input/blob/master/img/4.png)

## Original Result

The accuracy of the neural network is 99% for the original data.

## State-of-the-art attack algorithms: 
## FGSM Algorithm & C&W Algorithm

FGSM: We find that this method reliably causes a wide variety of models to misclassify their input by causing a small  shift in the values of the input. 

C&W: Dataset: Digit-recognition task (0-9) standard dataset MNIST
Measure of modification: Throughout our project, we have used the L2 distance. It measures the standard Euclidean (root mean-square) distance between x and x’ .

Motivation for L2:
The L2 norm is more stable than the L1 norm, although more rigorous to compute. L2 has just one solution compared to L1 which has multiple

## For FGSM, the accuracy is 29.8%, and images generated are as follows:

## For CW, the accuracy is 22.5%, and images generated are as follows:

  
