# neural-networks-in-PyTorch

Neural networks are computational models inspired by the human brain, designed to recognize patterns and solve complex tasks such as classification, regression and generation. In this article, we’ll explore how to build and train a simple neural network in PyTorch.

PyTorch offers two primary methods for building neural networks:

Using nn.Module: To create a custom network, subclass the nn.Module class and define the __init__ and forward functions. The __init__ method sets up the layers and parameters, while the forward function defines how input flows through the network and produces output.
Using nn.Sequential: This container allows you to specify layers in a list. The layers are automatically connected in the order provided.
Implementing Feedforward Neural Network for MNIST using PyTorch
Let's implement a Feedforward Neural Network (FNN) for classifying handwritten digits from the MNIST dataset using PyTorch.
