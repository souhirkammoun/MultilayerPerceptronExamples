# Introduction to Multilayer Neural Networks with KERAS
##### Introduction to  KERAS
- Keras is an API that sits on top of Google’s TensorFlow, Microsoft Cognitive Toolkit (CNTK), and other machine learning frameworks. The goal is to have a single API to work with all of those and to make that work easier.
- Keras is a high-level API for building neural networks that run on top of TensorFlow, Theano or CNTK. It allows for rapid prototyping, supports both recurrent and convolutional neural networks and runs on either your CPU or GPU for increased speed.
![](https://camo.githubusercontent.com/0d08dc4f9466d347e8d28a951ea51e3430c6f92c/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f6b657261732e696f2f696d672f6b657261732d6c6f676f2d323031382d6c617267652d313230302e706e67)
Use Keras if you need a deep learning library that:
- Allows for easy and fast prototyping (through user friendliness, modularity, and extensibility).
- Supports both convolutional networks and recurrent networks, as well as combinations of the two.
- Runs seamlessly on CPU and GPU.
Visit our presentation to leran more about MLP : https://urlz.fr/bibz;
See a complete example in : https://github.com/souhirkammoun/MultilayerPerceptronExamples/blob/master/MLPinKeraswithIRISdataset.ipynb
##### Multilayer Perceptrons
- Multilayer feedforward neural networks are a special type of fully connected network with multiple single neurons. They are also called Multilayer Perceptrons (MLP). The following figure illustrates the concept of an MLP consisting of three layers:


![](https://res.cloudinary.com/practicaldev/image/fetch/s--5hmoQpw5--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://cdn-images-1.medium.com/max/720/1%2AvWRGnasRs2zo3GhTHlmIfg.jpeg)

- The MLP depicted in the preceding figure has one input layer, one hidden layer, and one output layer. The units in the hidden layer are fully connected to the input layer, and the output layer is fully connected to the hidden layer. If such a network has more than one hidden layer, we also call it a deep artificial neural network.

#### MNIST
The MNIST dataset in four parts, as listed here:
- Training set images: x_train-images — 60,000 samples
- Training set labels: y_train-labels- — 60,000 labels
- Test set images: x_test— 10,000 samples
- Test set labels: y_labels — 10,000 labels

The training set consists of handwritten digits from 250 different people (50% high school students, 50% employees from the Census Bureau). The test set contains handwritten digits from different people.
-  The following figure illustrates our simple artificial neural network in the first example:
![](https://github.com/sausheong/pynn/raw/master/imgs/nn.png)

- The neural network had 3 layers, the first (input) layer has 784 neurons (28 x 28 pixels), the second (hidden) layer has 512 neurons and the final (output) layer has 10 neurons.
####  Iris 
- This is the "Iris" dataset. Originally published at UCI Machine Learning Repository: Iris Data Set, this small dataset from 1936 is often used for testing out machine learning algorithms and visualizations (for example, Scatter Plot). Each row of the table represents an iris flower, including its species and dimensions of its botanical parts, sepal and petal, in centimeters.
![](https://upload.wikimedia.org/wikipedia/commons/thumb/5/56/Iris_dataset_scatterplot.svg/220px-Iris_dataset_scatterplot.svg.png)

- The implementation of a multilayer perceptron neural network from scratch on the famous 'iris' dataset. In this model, I present a three layer neural network with a relu activation function for the hidden layer and a softmax activation function for the output layer.

- Attribute Information:

1. sepal length in cm
1. sepal width in cm
1. petal length in cm
1. petal width in cm
1. class:
-- Iris Setosa
-- Iris Versicolour
-- Iris Virginica




- All the implementations below follow the same generic steps:

1. Set up the parameters and load the datasets (most frameworks have a means to load standard datasets like MNIST)
1. Define the neural network by creating a mlp function that creates and returns the neural network
1. Define the train function
1. Define the predict function
1. Create a main that allows the user to first train using the training dataset (60,000 images) then predict using the test dataset (10,000 images)
 - For this project we used Google's cloud IDE Colaboratory to develop in,  It is simple and better way of learning machine learning and deep learning on cloud


----------------------------------------------------------
###### Copyright © 2019 developped by ***Avengers Isi***
------------------------------------------------------------

