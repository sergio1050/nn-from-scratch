# Neural Network for Image Classification

This is a simple implementation of a two-layer neural network for image classification. The script is written in Python, using NumPy, Pandas, and Matplotlib libraries.

The neural network uses the ReLU activation function for the hidden layer and the softmax function for the output layer. The network is trained using gradient descent.

## Getting Started

### Prerequisites

This script requires the following libraries installed on your machine:
- Numpy
- Pandas
- Matplotlib

## Data Format
The script assumes you have a .csv file with the name train.csv located in the same directory. The first column of this .csv file should represent the labels (integer values) of the dataset, and the rest of the columns represent the pixel values of the images (784 pixels or a 28x28 image).

## Code Details
### Initialization
- The script first loads the dataset, normalizes it, and splits it into training and development sets.
- Then, it initializes the parameters of the network.

## Forward Propagation

- It calculates the Z values and activation A for each layer.
## Backward Propagation
- It calculates the gradients for each parameter in the network.
## Parameters Update
- The parameters of the network are updated in the direction of the negative gradient.
## Training
- The network is trained using the training dataset.
- The accuracy of the network on the training dataset is printed every 10 iterations.
## Prediction
- After the training process, the network can make predictions on new unseen data.
- A test function is available that makes a prediction for a given image index from the training set, prints the prediction, the true label, and the image itself.
## Running the Code

## Notes
1. This code does not currently handle any exceptions or errors, so make sure the data is in the correct format.
2. You can adjust the learning rate and the number of iterations in the gradient descent function call. Be aware that higher learning rates may cause the model to converge faster, but it may also overshoot the minimum. A lower learning rate could lead to better results, but it would require more iterations.
3. This code is for educational purposes and may not be optimized for production environments.


