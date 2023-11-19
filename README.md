# 7-segment-indicator
Training a neural network to simulate the operation of a 7 segment indicator with 10 outputs. Visualization of the indicator.

A neural network is a multi-layered perceptron. The number of layers is 4, the number of inputs is 7 (by the number of segments), the number of outputs is 10 (by the number of possible options from 0 to 9). The outputs are competing against each other. Each output is responsible for one of the options, it is he who will be equal to 1 in the training sample, all other outputs are 0).
For a more visual demonstration of the model's operation, the visualization of inputs in the form of a 7-segment indicator is used.
