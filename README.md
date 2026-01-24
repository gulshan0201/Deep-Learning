# Deep-Learning
## What  is forward propogation?
Forward propagation is the process in a neural network where input data moves sequentially from the input layer, through hidden layers, to the output layer to generate a prediction, using weights, biases, and activation functions at each step. It's essentially the "doing" part of a network, where data flows in one direction to compute an output, forming the basis for training when paired with backpropagation to adjust parameters. 
### How it works
* Input Layer: Raw data (features) enters the network.
* Hidden Layers: Data is transformed in stages:
* Inputs are multiplied by weights and a bias is added.
* This sum passes through an activation function (like ReLU or sigmoid) to introduce non-linearity.
* The result becomes the input for the next layer.
* Output Layer: The final layer produces the network's prediction or output (e.g., a classification, a number)
