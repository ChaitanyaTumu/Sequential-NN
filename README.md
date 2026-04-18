# Solving the Non-Linear XOR Problem using a Sequential Neural Network

## 🌟 Project Overview
This project demonstrates the implementation of a basic Artificial Neural Network (ANN) using **TensorFlow** and **Keras** to solve the classic **XOR (Exclusive OR)** logic gate problem. 

The XOR problem is historically significant in the field of deep learning. While a single-layer perceptron can solve linear problems (like AND/OR gates), it fails at XOR because the data points are not linearly separable. By introducing a hidden layer with non-linear activation functions, this Multi-Layer Perceptron (MLP) successfully learns the underlying mapping of the XOR function.

## 🎯 Key Objectives
* Construct a Multi-Layer Perceptron (MLP) using the Keras `Sequential` API.
* Understand the necessity of hidden layers for non-linear data separability.
* Configure hyperparameters including Stochastic Gradient Descent (SGD), learning rate, and Mean Squared Error (MSE) loss.
* Train the model and evaluate its predictive accuracy on boolean inputs.

## 🛠️ Technology Stack
* **Python 3**
* **TensorFlow / Keras** (Deep Learning framework)
* **NumPy** (Data manipulation)

## 🧠 Model Architecture
1. **Input Layer:** 2 features (representing the two binary inputs of an XOR gate).
2. **Hidden Layer:** 3 neurons with a `Sigmoid` activation function to handle non-linearity.
3. **Output Layer:** 1 neuron with a `Sigmoid` activation function to output a probability between 0 and 1.

## 📊 Dataset
The network is trained on the standard XOR truth table:
| Input 1 | Input 2 | Output |
|---------|---------|--------|
| 0       | 0       | 0      |
| 0       | 1       | 1      |
| 1       | 0       | 1      |
| 1       | 1       | 0      |

## 🚀 How to Run
1. Clone this repository or download the `.ipynb` notebook.
2. Open the notebook in [Google Colab](https://colab.research.google.com/) or any local Jupyter environment.
3. Run all cells sequentially to see the model architecture, training loss reduction, and final predictions.
