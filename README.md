# Digit_Recognizer 🧠✍️

A Python-based neural network that recognizes handwritten digits from the MNIST dataset, built **from scratch without using machine learning libraries** like TensorFlow or PyTorch. This project demonstrates the fundamentals of neural network architecture and training processes using only NumPy.

## 🚀 Features

- **Custom Neural Network Implementation**: Built a two-layer neural network using only NumPy, without external ML libraries.
- **MNIST Dataset Utilization**: Trained and tested the model on the MNIST dataset, consisting of 28x28 pixel grayscale images of handwritten digits.
- **Educational Focus**: Emphasizes understanding of neural network operations, including forward propagation, activation functions, backpropagation, and gradient descent.

## 🧠 How It Works

1. **Data Preprocessing**: Normalizes pixel values and splits the dataset into training and development sets.
2. **Network Architecture**:
   - **Input Layer**: 784 units (28x28 pixels).
   - **Hidden Layer**: 10 units with ReLU activation.
   - **Output Layer**: 10 units (corresponding to digits 0–9) with softmax activation.
3. **Training Process**:
   - **Forward Propagation**: Computes activations for each layer.
   - **Loss Calculation**: Uses categorical cross-entropy to measure prediction error.
   - **Backward Propagation**: Computes gradients of loss with respect to weights and biases.
   - **Parameter Updates**: Adjusts weights and biases using gradient descent.

## 🧰 Tech Stack

- **Python**
- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation.
- **Matplotlib**: For visualizing results.



