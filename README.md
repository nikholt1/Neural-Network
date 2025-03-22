# Neural Network

This project implements a simple feedforward neural network using Python and NumPy. 
The network takes an input vector, applies weights and biases, and uses the sigmoid activation function to make predictions. 
Gradient descent is used to update the weights and minimize the mean squared error (MSE), improving the model's accuracy over time.
## Usage
```
python python neural_network3.py
```


## Features:
- Feedforward neural network with adjustable weights and biases
- Implementation of the sigmoid activation function
- Gradient descent to reduce error through iterative weight updates
- Example input, output, and error calculation
- Outputs plot .png file with training error across iterations.

### Training error across iterations

![image](https://github.com/user-attachments/assets/19c02df3-c738-4277-b8dd-97ce637c8d21)


## Visualization 
### Input layer:
- Contains two input neurons representing x1 and x2. These are plotted as blue circles.

### Hidden layer:
- This neuron performs a weighted sum of the inputs and applies a sigmoid activation function.

### Output Layer:
- Contains one output neuron, drawn as a red circle. This neuron outputs the final prediction after processing through the network.

### Connections (Synapses):
Represented by black lines connecting neurons from the input to hidden and from the hidden to the output layer. 
These lines visualize the flow of information and weight propagation during forward pass computation.

![image](https://github.com/user-attachments/assets/af7b8120-a357-4b25-973a-6e4daf677bfb)



