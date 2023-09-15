# MNIST-handwritten-digit-recognizer

The MNIST Handwritten Digit Recognizer is a machine learning project that uses a neural network to recognize handwritten digits from the MNIST dataset. It's a classic problem in machine learning.
The project's main goal is to train a neural network for image classification tasks and making predictions on new handwritten digits.

### Dataset

The project uses the MNIST dataset, which consists of 28x28 pixel grayscale images of handwritten digits (0-9). It's a widely used dataset for digit recognition tasks and contains a training set of 60,000 images and a test set of 10,000 images.

### Usage

- Training: The neural network is trained on the MNIST training dataset, which is loaded automatically.
- Testing: You can evaluate the model's performance on the test dataset. Metrics like accuracy and mean absolute error are displayed.
- Prediction: Use the project to make predictions on handwritten digits.

Provide your own images or use the provided test dataset for predictions.

### Model Architecture

The neural network architecture used for this project consists of:

- Input Layer (784 units): Flattened 28x28 pixel images.
- Hidden Layer 1 (512 units): Activation function - ReLU.
- Hidden Layer 2 (512 units): Activation function - ReLU.
- Output Layer (10 units): Activation function - Softmax.

### Evaluation

The model's performance is evaluated using the test dataset:
- Loss: Sparse Categorical Cross-Entropy.
- Metrics: Mean Absolute Error (MAE) and Accuracy.

The evaluation results are displayed after training the model.

<img width="604" alt="Screenshot 2023-09-15 at 12 26 33 PM" src="https://github.com/Satwik260204/MNIST-handwritten-digit-recognizer/assets/121714021/e87a2164-c060-4b8a-ba99-36cf13abc0fa">




