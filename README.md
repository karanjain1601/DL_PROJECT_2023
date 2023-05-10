# DL_PROJECT_2023
Project for DL course 2023

## INTRODUCTION
We demonstrate the implementation of the "Shake-Drop Regularisation for Deep Residual Learning" paper in this study. In order to enhance the performance of deep residual networks, the paper suggests a novel regularisation technique called Shake-Drop, which combines the advantages of two already-existing techniques, Shake-Shake and DropBlock. This project aims to examine the efficiency of the Shake-Drop regularisation approach and validate the results presented in the published research. Regularisation is an essential deep learning technique since it reduces overfitting and improves neural network generalization. Through advancing regularisation methods in deep learning, this project will be advantageous to the scientific community.

## BACKGROUND
Regularisation methods are necessary for deep learning because they increase neural network generalization and reduce overfitting. In order to prevent co-adaptation, the regularisation technique known as "dropout" randomly removes neurons during training. L1 or L2 regularisation, which adds a penalty term to the loss function to encourage moderate weight values, is another extensively used approach. 
The performance of deep learning models has recently been improved by a number of neural network topologies. ResNet, PyramidNet, and ResNeXt are a few of them. ResNet makes use of skip connections and permits deeper designs to assist with the vanishing gradient issue. PyramidNet creates a pyramidal form for the network to encourage feature reuse and lower processing costs. ResNeXt is based on ResNet, but instead of broadening or deepening the network to boost the model's capacity, it employs a cardinality parameter.


## How to run Codes
### install all the dependencies


torchvision


tensorboard


WandB


Ipython


torchsummary


torch.autograd


## CONCLUSION
In this study, a deep residual network architecture was given the Shake-Drop regularisation technique, and its effectiveness was contrasted with dropout and no regularisation. Our findings demonstrate that shake-drop is more effective at eliminating overfitting and attaining higher test accuracy than dropout and no regularisation. Our findings demonstrate that Shake-Drop is a potential regularisation technique for deep residual networks, even though it's possible that our implementation's outcomes may differ slightly from those of the original research due to changes in the datasets. Our research highlights the importance of regularisation techniques in deep learning and their potential to enhance neural network generalization.


## REFERENCES
https://medium.com/swlh/paper-shakedrop-shakedrop-regularization-for-deep-residual-learning-image-classification-d2b83d0ae3de


https://arxiv.org/abs/1802.02375


https://github.com/owruby/shake-drop_pytorch




