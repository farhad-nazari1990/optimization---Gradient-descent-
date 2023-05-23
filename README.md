# optimization---Gradient-descent-
optimization - Gradient descent : linear and non-linear function

# Gradient Descent Models

This repository contains code for training and comparing two gradient descent models: Model 1 and Model 2. These models are used to predict temperature values based on input data.

## Dataset

The dataset used in this project consists of two variables:

- `t_c`: The target temperature values
- `t_u_normalized`: The input temperature values, normalized between 0 and 1

## Models

The two models implemented are:

1. Model 1: A linear model that predicts temperature using a single weight `w` and a bias `b`. The prediction is given by `t_p = w * t_u_normalized + b`.
2. Model 2: A non-linear model that predicts temperature using three weights `w1`, `w2`, and `w3`, and a bias `b`. The prediction is given by `t_p = w3 * t_u_normalized^2 + w2 * t_u_normalized + b`.

## Training

The models are trained using gradient descent optimization to minimize the mean squared error loss function. The training process involves updating the model parameters iteratively over a specified number of epochs.

## Results

After training the models, the final loss values are as follows:

- Model 1: Final Loss = {losses1[-1]}
- Model 2: Final Loss = {losses2[-1]}

## Usage

To use this code, make sure you have Python and the required dependencies installed. Simply run the provided script, and the models will be trained and the loss function plotted.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


