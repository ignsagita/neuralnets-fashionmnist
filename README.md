# Classification task using Custom Neural Networks in PyTorch for the Fashion MNIST case
## Overview
This project performs regression task on the [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) from *Zalando Research* data. The goal is to classify wheter a picture of fashion belongs to which label.

## Description
- Import PyTorch and load a sample dataset automatically
- Sequential fully connected network: training and test
- Save the model

## Dataset
The dataset has the same property as a normal MNIST, but the images represent fashion items rather than handwritten digits, 
which means it might have more complexity than normal MNIST.

Because of its complexity in each class, the problem is slightly more challenging than normal MNIST. 
For example, a simple linear model reaches about 92% accuracy on MNIST, but only about 83% on Fashion MNIST. Moreover, MNIST is overused.
In this April 2017 Twitter thread, Google Brain research scientist and deep learning expert Ian Goodfellow calls for people to move away from MNIST. 
In addition, MNIST can not represent modern CV tasks, as noted in this April 2017 Twitter thread, deep learning expert/Keras author François Chollet.

It has **70,000 article images**. Each example is a 28x28 grayscale image, associated with a label from 10 classes.

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

## Quick Start
- Clone this repository: git clone https://github.com/ignsagita/neuralnets-fashionmnist.git cd neuralnets-fashionmnist
- Install dependencies pip install -r requirements.txt
- Recommended Setup: For the best experience, **run this notebook on [Google Colab](https://colab.research.google.com/)** 
- In Colab, **enable GPU support** by going to: `Runtime > Change runtime type > Hardware accelerator > GPU`

---
