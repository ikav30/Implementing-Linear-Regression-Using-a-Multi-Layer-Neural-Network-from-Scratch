# Implementing Linear Regression Using a Multi-Layer Neural Network from Scratch

Dataset Description: Use the Boston Housing Dataset[ Link ]. Focus on 
predicting the median value [ ‘MEDV’ ] of homes based on two features
● Number of Rooms (`RM`)
● Crime Rate (`CRIM`)

Data Preprocessing:
● Normalize the features to ensure they are on a similar scale.
● Split the dataset into a training set (80%) and a test set (20%).
Model:
In this assignment, you will build a neural network from scratch to perform linear 
regression using Python. You will be implementing a multi-layer neural network 
with multiple hidden layers.

Details of the Architecture:
Input Layer:
● Number of Neurons: Equal to the number of features in the dataset (e.g., 
2 input neurons if using 2 features from the Boston Housing Dataset).
Number of Hidden Layers: 2 hidden layers.
First Hidden Layer:
● Number of Neurons: 5 neurons.
● Activation Function: ReLU (Rectified Linear Unit) for non-linearity.
Second Hidden Layer:
● Number of Neurons: 3 neurons.
● Activation Function: ReLU (Rectified Linear Unit).
Output Layer:
● Number of Neurons: 1 neuron, since the task involves predicting a single 
continuous value (e.g., house price).
.
Training the Network:
1) Implement Gradient Descent for weight updates.
2) Experiment with different learning rates (e.g., 0.01, 0.001) to observe the 
effects on model training.
3) Train the network for a set number of epochs (e.g., 1000 epochs) and track 
the loss throughout the training process.
4) Implement and compare different optimizers:
a) Basic Gradient Descent
b) Momentum
c) Adam
5) Observe and compare how these optimizers affect the model’s 
convergence and final performance.

Evaluation:
1. Evaluate the trained model on a test set.
2. Visualize the regression results by plotting the predicted vs. actual values.
3. Calculate evaluation metrics such as Mean Squared Error (MSE) on the 
test data to quantitatively assess the model’s performance.
