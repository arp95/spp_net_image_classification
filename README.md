# CNN Architectures(with and without SPP Layer) for Image Classification

[![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg)](LICENSE.md)
---


### Author
Arpit Aggarwal


### Introduction to the Project
In this project, different CNN Architectures like VGG-16(with and without SPP Layer), VGG-19(with and without SPP Layer), and ResNet-50(with and without SPP Layer) were used for the task of Dog-Cat image classification. The input to the CNN networks was a (224 x 224 x 3) image and the number of classes were 2, where '0' was for a cat and '1' was for a dog. The CNN architectures were implemented in PyTorch and the loss function was Cross Entropy Loss. The hyperparameters to be tuned were: Number of epochs(e), Learning Rate(lr), momentum(m), weight decay(wd) and batch size(bs). 


### Data
The data for the task of Dog-Cat image classification can be downloaded from: https://drive.google.com/drive/folders/1EdVqRCT1NSYT6Ge-SvAIu7R5i9Og2tiO?usp=sharing. The dataset has been divided into three sets: Training data, Validation data and Testing data. The analysis of different CNN architectures for Dog-Cat image classification was done on comparing the Training Accuracy and Validation Accuracy values.


### Results
The results after using different CNN architectures are given below:

1. <b>VGG-16(without SPP Layer, pretrained on ImageNet)</b><br>

Training Accuracy = 99.27% and Validation Accuracy = 96.73% (e = 100, lr = 0.005, m = 0.9, bs = 32, wd = 0.001)<br>


2. <b>VGG-16(with SPP Layer)</b><br>

Training Accuracy = 99.61% and Validation Accuracy = 97.23% (e = 100, lr = 1e-3, m = 0.9, bs = 32, wd = 5e-4)<br>


3. <b>VGG-19(without SPP Layer, pretrained on ImageNet)</b><br>

Training Accuracy = 99.13% and Validation Accuracy = 97.25% (e = 100, lr = 0.005, m = 0.9, bs = 32, wd = 5e-4)<br>


4. <b>VGG-19(with SPP Layer)</b><br>

Training Accuracy = 99.51% and Validation Accuracy = 97.45% (e = 100, lr = 1e-3, m = 0.9, bs = 32, wd = 5e-4)<br>


5. <b>ResNet-50(without SPP Layer, pretrained on ImageNet)</b><br>

Training Accuracy = 99.43% and Validation Accuracy = 98.43% (e = 100, lr = 0.005, m = 0.9, bs = 32, wd = 5e-4)<br>


### Software Required
To run the jupyter notebooks, use Python 3. Standard libraries like Numpy and PyTorch are used.


### Credits
The following links were helpful for this project:
1. https://github.com/yueruchen/sppnet-pytorch/
2. https://discuss.pytorch.org/t/elegant-implementation-of-spatial-pyramid-pooling-layer/831
