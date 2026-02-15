# Lab 1: Feedforward Neural Network from Scratch

## Objective

Implement a simple Feedforward Neural Network from scratch using Python and NumPy only (no deep learning frameworks) to solve the XOR problem.

---

## 📋 Problem Statement

The XOR (exclusive OR) function is a classic problem in neural networks that cannot be solved by a single-layer perceptron. This lab demonstrates how a neural network with a hidden layer can learn the non-linear XOR function.

### XOR Truth Table

| Input 1 | Input 2 | Output |
|---------|---------|--------|
| 0       | 0       | 0      |
| 0       | 1       | 1      |
| 1       | 0       | 1      |
| 1       | 1       | 0      |

---

## 🏗️ Network Architecture

- **Input Layer:** 2 neurons
- **Hidden Layer:** 3 neurons (with sigmoid activation)
- **Output Layer:** 1 neuron (with sigmoid activation)

---

## 🔬 Implementation Details

### Key Concepts Implemented:

1. **Forward Propagation**
   - Linear combination: z = W·x + b
   - Sigmoid activation: σ(x) = 1/(1 + e^(-x))

2. **Loss Function**
   - Mean Squared Error (MSE)

3. **Backpropagation**
   - Gradient computation using chain rule
   - Output layer gradients
   - Hidden layer gradients

4. **Gradient Descent**
   - Weight updates: W = W - α·∇W
   - Bias updates: b = b - α·∇b

### Hyperparameters:

- **Learning Rate:** 0.1
- **Epochs:** 100
- **Random Seed:** 42 (for reproducibility)

## 📊 Results

The network successfully learns the XOR function, achieving high accuracy after training. The loss decreases over epochs, showing that the network is learning.

---

## 💻 How to Run

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook Neural_Network.ipynb
   ```

2. Run all cells sequentially (Cells 1-13)

3. Observe:
   - Initial weights
   - Training progress (loss per epoch)
   - Final weights and predictions
   - Accuracy metrics

---

## 📚 Key Learnings

- ✅ Understanding forward propagation
- ✅ Implementing backpropagation manually
- ✅ Gradient descent optimization
- ✅ Why hidden layers are necessary for non-linear problems
- ✅ Neural network training dynamics

---

## 🔧 Technologies

- Python 3.x
- NumPy
- Jupyter Notebook

---

## 📝 Notes

This implementation uses **only NumPy** - no TensorFlow, Keras, or PyTorch. This helps in understanding the fundamental mathematics behind neural networks before using high-level frameworks.

---

**Date:** February 14, 2026  
**Course:** Deep Learning

