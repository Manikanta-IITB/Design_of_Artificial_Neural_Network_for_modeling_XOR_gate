# Design of Artificial Neural Network for modeling XOR gate
This repository contains the implementation of a logical XOR gate using a neural network with a single hidden layer. The neural network architecture and weights are designed to achieve XOR functionality. The repository provides code, explanations, and visualizations to help understand the process.

![XORNN drawio](https://github.com/Manikanta-IITB/Design_of_Artificial_Neural_Network_for_modeling_XOR_gate/assets/138108630/03195a8b-379c-45c7-a642-0793a64a8161)

## Table of Contents
1) Introduction
2) Neural Network Architecture
3) XOR Gate Implementation
   
## Introduction:
In this section, provide a brief overview of the project, explaining the goal of implementing an XOR gate using a neural network and the importance of the single hidden layer architecture.

## Neural Network Architecture:
Explain the architecture of the neural network, detailing the input layer, hidden layer, and output layer. Discuss the activation functions used (e.g., sigmoid) and the choice of weights for the hidden layer.

## XOR Gate Implementation:
Describe how the neural network architecture is tailored to implement the XOR gate logic. Discuss how the combination of NOR and AND gates in the hidden layer leads to XOR functionality. we have two input neurons or x vector having values as x1 and x2 and 1 being the bias value. The input values, i.e., x1, x2, and 1 is multiplied with their respective weight matrix that is W1, W2, and W0. The corresponding value is then fed to the summation neuron where we have the summed value which is

![Xor_NN](https://github.com/Manikanta-IITB/Design_of_Artificial_Neural_Network_for_modeling_XOR_gate/assets/138108630/14be1c88-f3d3-4ef1-86db-390851113619)

## Sigmoid Activation Function
The sigmoid activation function is a widely used non-linear function in neural networks. It's also known as the logistic function due to its S-shaped curve. The sigmoid function takes an input value and maps it to a value between 0 and 1. This property makes it particularly useful for introducing non-linearity in neural networks, allowing them to model more complex relationships in the data.

![sigmoid2](https://github.com/Manikanta-IITB/Design_of_Artificial_Neural_Network_for_modeling_XOR_gate/assets/138108630/f007129e-4b8d-4a66-948d-6c2bef06b0ec)


