STRUCTURE FOR OUR NN MODEL: 
    INPUT: 8 neurons
    HIDDEN LAYERS (3): 25 neurons, 50 neurons, 6 neurons
    OUTPUT: 2 neurons

IMPORTANT THINGS (about making an NN with Pytorch)
- TURNING DATA INTO TENSORS -> so the nn math can be easier
- NORMALIZE THE DATA -> so that everything is on the same scale
- SETTING A LEARNING RATE (0.0 to 1.0): 0.001 -> controls how quickly the model adapts to the problem
- OPTIMIZER: Adam -> used to optimize the model and minimize the loss function at each itertion of the model
- LOSS FUNCTION: Mean Squared Error
- ACTIVATION FUNCTION: using ReLU

Additional Considerations about the NN Model:

- Remember that the choice of number of neurons in the hidden layer is an initial configuration. You might need to experiment with different numbers of neurons or hidden layers to find the optimal architecture for your specific dataset and task.
- While your model structure is appropriate, the training process is crucial for learning effective weights and biases in each layer. The combination of your chosen architecture, chosen loss function (Mean Squared Error), optimization algorithm, and hyperparameter tuning will significantly impact the model's performance and ability to accurately predict the coordinates.


