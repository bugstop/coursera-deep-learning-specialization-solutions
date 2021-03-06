---
title: Deep Learning (1) · Introduction
date: 2020-03-24 17:20:30
tags: [Artificial Intelligence, Deep Learning]
categories: [Open Course, Deep Learning]
mathjax: true
---

Deep Learning Specialization, Course A
**Neural Networks and Deep Learning** by deeplearning.ai, **_Andrew Ng,_** [Coursera](https://www.coursera.org/learn/neural-networks-deep-learning/home/info)

**_Week 1:_** _Introduction to Deep Learning_

1. Understand the major trends driving the rise of deep learning.
2. Be able to explain how deep learning is applied to supervised learning.
3. Understand what are the major categories of models (such as CNNs and RNNs), and when they should be applied.
4. Be able to recognize the basics of when deep learning will (or will not) work well.

<!-- more -->

### Introduction to Deep Learning

#### What is a Neural Network?

![House Price](Deep-Learning-Andrew-Ng-1/house-price.png)

**ReLU,** Rectified Linear Unit Function: $\max\left(0,y\right)$

![What is a neural network?](Deep-Learning-Andrew-Ng-1/1.png)

**Notice** that each of these hidden units in the neural network takes its inputs all four input features. **_(density connected)_**

![What is a neural network?](Deep-Learning-Andrew-Ng-1/2.png)

#### Supervised Learning with Neural Networks

- **standard neural network**
- **convolution on neural networks, CNN:** image applications
- **recurrent neural network, RNN:** sequence data
- **custom / hybrid**

![Neural Networks](Deep-Learning-Andrew-Ng-1/nn.png)

- **Structured Data:** features have well defined meanings
- **Unstructured Data:** audio / image / text

#### Why is Deep Learning Taking off?

- **Data**
  **_m:_** size of training sets / number of training examples &emsp; _(on small training sets: feature engineering)_
  ![Scale](Deep-Learning-Andrew-Ng-1/scale.png)
- **Computation**

- **Algorithms**
  **_activation function:_** Sigmoid → ReLU
  ![Activation Function](Deep-Learning-Andrew-Ng-1/relu.png)
