# MNIST Handwritten Digit Classification

*Used various Multilayer Perceptron (MLP) and Convolutional Neural Network (CNN) Models for MNIST Handwritten Digit Classification Problem using Keras.*

## Digit Classification - MLP

*Following combinations of models are used for classifying handwritten digits using MLP :-*

1. MLP + ReLU + ADAM + 2 hidden layers
2. MLP + ReLU + ADAM + 2 hidden layers + Batch Normalization
3. MLP + ReLU + ADAM + 2 hidden layers + Dropout
4. MLP + ReLU + ADAM + 3 hidden layers
5. MLP + ReLU + ADAM + 3 hidden layers + Batch Normalization
6. MLP + ReLU + ADAM + 3 hidden layers + Dropout
7. MLP + ReLU + ADAM + 5 hidden layers
8. MLP + ReLU + ADAM + 5 hidden layers + Batch Normalization
9. MLP + ReLU + ADAM + 5 hidden layers + Dropout

## Digit Classification - CNN

*Following combinations of models are used for classifying handwritten digits using CNN :-*

1. 12 Epochs + (3,3) Kernel size + ReLU + AdaDelta + (0.15,0.30) Dropout rates 
2. 15 Epochs + (5,5) Kernel size + ReLU + AdaDelta + (0.40,0.60) Dropout rates
3. 20 Epochs + (7,7) Kernel size + ReLU + AdaDelta + (0.50,0.80) Dropout rates

## Steps Followed

- Load the MNIST dataset.
- Train and test split of the MNIST dataset.
- Normalize the train and test data.
- Converting class variable into categorical data vector.
- Implement Softmax Classifier.
- Trying out different MLP and CNN architectures with different activation functions, optimizers, kernel size, dropout rates and different number of layers on MNIST dataset.
- Draw categorical crossentropy loss vs number of epochs plot.
- Draw violin plots for hidden layers and output layer.
- At the end in the conclusion section compare training and test log loss for each model.
