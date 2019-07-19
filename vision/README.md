# EEML2019: ConvNets and Computer Vision Tutorial
by Viorica Patraucean

_Designed for education purposes. Please do not distribute without permission_.

**Questions/Correspondence**: vpatrauc@gmail.com

## PART I
### Supervised classification, overfitting and inductive biases in convnets, and how to improve models through self-supervision

* Exercise 1: Implement and train a Resnet-50 classifier using supervised learning; enable/disable batch norm updates to see the effect.
* Exercise 2: Inductive biases in convnets; comparison with MLP.
* Exercise 3: Overfitting and regularization using weight decay.
* Exercise 4: Enable self-supervised learning using data augmentation.

## PART II
### Knowledge distillation: Distilling a pre-trained teacher model into a smaller student model 

* Define student model (custom Resnet-21)
* Load pre-trained teacher model (Resnet-50) 
* Add KL distillation loss between teacher and student
* Observe the impact of temperature in softmax for teacher predictions
* Train student with the joint loss
