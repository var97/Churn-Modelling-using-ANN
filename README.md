# Artificial Neural Networks

Artificial Neural Networks are basically a collection of interconnected nodes/neurons representing the similar structure as human brain.
Each connection, like the synapses in a biological brain, can transmit a signal from one artificial neuron to another. An artificial neuron that receives a signal can process it and then signal additional artificial neurons connected to it.It primarily consists of three layers:

- Input Layer
- Hidden Layer
- Output Layer

## Working of ANN

- The input layer takes input values after preprocessing in the neurons from the dataset.
- Then for each particular neuron in the hidden layer the input is calculated by multiplying the values of inputs of each neuron from input layer connected to that particular neuron by the weights of the each particular edges that are connecting those neurons to that particular neuron.
- After that value of bias node is added and then we have to apply appropiate activation function to the whole calculated value to get the scaled data for next layer as a input

For example if their are x1, x2 and x3 as an input values and w1, w2, w3 as weight of edges connecting to neuron h1 in hidden layer, then input of h1 is calculated by

h1 = activation function(x1*w1 + x2*w2 +x3*w3 +biasnode)

- And same process is repeated for generating the input value of each neuron in hidden layer and then those inputs are passed to the output layer and same process is repeated again to gain the ouptut. 

In order to gain best output from multi layer neural networks backpropagation algorithm is used by ANN through which weights are adjusted accordingly and best output will be obtained.

Well we can also use hyperparameter tuning in order to achieve the best parameters for an ANN so that it could achieve better results.

** I recommend all to user to use  _hyperparameter tuning_ so that they can achieve best from their ANN. Well I have also used hyperparameter tuning in my code **

Well this is the working of an ANN,  most of this you are unable to see practically because this is basically what happens behind the scenes.

## Customer Churn Problem

In this project I am analysing the bank data and try to predict that which customers are going to leave the bank in coming days. This can be also be considered as Geo-demographic Segmentation Model. 

If you have any query mail me at: readervarun97@gmail.com

