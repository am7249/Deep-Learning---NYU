# Deep-Learning---NYU
This repository contains the projects done for Deep Learning class at NYU for Spring 2018.

The file named DNN1.ipynb contains the code for implementing a Deep Neural Network from scratch without using any Deep Learning framework. All the processes in forward propagation and backward propagation are implemented from scratch using numpy operations only.
The dataset used is the CIFAR-10 dataset, with 50000 training images and 10000 testing images.

The activation funcions implemented in this file are ReLU, Leaky ReLU, and Swish. The optimization algorithms implemented are Adam and SGD. 
I further plan to enrich the file by adding more variants of activation functions, optimization algorithms.

I have also implemented Dropout Regularization and L2 regularization for the network. Moreover, I plan to implement Batch Normalization, L1, and Data Augmentation. 

The hyperparameters can be tuned by the user to modify the net and possibly achieve better result. I trained the model on AWS p2.xlarge instance, which provides GPU usage as training on CPU takes a lot of time.

I was able to obtain a validation accuracy of >56%, which also explains why simple deep nets are not the best choice for image recognition and why we use Convolutional Neural Networks.
