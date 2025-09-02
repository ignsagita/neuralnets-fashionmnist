# Fashion-MNIST classification task using Custom NN and Convolutional NN in PyTorch
## Overview
This project demonstrates how to build, train, and evaluate custom neural networks and CNN on the [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) from *Zalando Research* data. The goal is to classify whether a picture of fashion belongs to the certain label.

## Description
The goal is to classify images of fashion items into 10 categories using different neural network architectures:
- A fully connected (MLP) network
- A simple convolutional neural network (CNN)

The notebook includes data handling, train/validation/test splits, early stopping, model saving, and feature visualization (feature map of CNN).

## Dataset
It has **70,000 grayscale images** of fashion articles 28x28 pixels, associated with a label from 10 classes.

**Labels** <br>
Each training and test example is assigned to one of the following labels:<br>
0	T-shirt/top<br>
1	Trouser<br>
2	Pullover<br>
3	Dress<br>
4	Coat<br>
5	Sandal<br>
6	Shirt<br>
7	Sneaker<br>
8	Bag<br>
9	Ankle boot

> Note: The dataset is **not included in this repository**. The notebook downloads the dataset automatically from Github.

** Why Fashion MNIST? **
The dataset has the same properties as a normal MNIST, but has more complexity than normal MNIST. In normal MNIST, a simple linear model reaches about 92% accuracy, but only about 83% on Fashion MNIST. Moreover, MNIST is overused. In this April 2017 Twitter thread, Google Brain research scientist and deep learning expert Ian Goodfellow calls for people to move away from MNIST. In addition, MNIST can not represent modern CV tasks, as noted in this April 2017 Twitter thread, deep learning expert/Keras author François Chollet.

## Quick Start
- Clone this repository: git clone https://github.com/ignsagita/class-nn_cnn-fashionmnist.git cd class-nn_cnn-fashionmnist
- Install dependencies pip install -r requirements.txt
- Recommended Setup: For the best experience, **run this notebook on [Google Colab](https://colab.research.google.com/)** 
- In Colab, **enable GPU support** by going to: `Runtime > Change runtime type > Hardware accelerator > GPU`


---
