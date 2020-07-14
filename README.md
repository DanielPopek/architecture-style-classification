# Architecture Style Classification

The aim of this project was to imlement simple image classifier of architectural styles for Kaggle competition. 

https://www.kaggle.com/t/a4028040af1343038c77f8f23b26e3fa

2 simple deep neural networks were implemnted in Tensorflow:

## Deep CNN network 
CNN classifier with Batch Normalization, ResNet-like skip connections, dropout in FullyConeccted layers

## VGG-16 like classifier 

Pretarined VGG-16 classifier with augmented dataset. 

## Effects

Models allow to achive 60% accuracy on test set. 

## Possible improvemnets 

Usage of inception modules from GoogleNet