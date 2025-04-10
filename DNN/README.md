# Feedforward Neural Networks (DNN) 🚀

Welcome to the Deep Neural Network (DNN) repository! This repo serves as a foundational resource for understanding and implementing **Feedforward Neural Networks (FFNN)** using Python and TensorFlow/Keras.

---

## 📌 What is a Feedforward Neural Network?

A **Feedforward Neural Network (FFNN)** is one of the simplest types of Artificial Neural Networks, where the flow of information is strictly in one direction—from input to output—without any cycles or loops.

It consists of:
- An **input layer** to receive data
- One or more **hidden layers** for processing
- An **output layer** to produce the result

Unlike recurrent networks, FFNNs do **not have memory** of past inputs.

---

## 🧠 Layers in FFNN

1. **Input Layer**
   - Takes the input features (e.g., sepal length, petal width).
2. **Hidden Layers**
   - Perform weighted computations and pass through activation functions.
   - You can have one or more hidden layers depending on the complexity of the problem.
3. **Output Layer**
   - Produces the final predictions or classifications.

---

## ⚙️ Phases in Training a FFNN

1. **Forward Propagation**
   - Input flows through the network.
   - Weighted sums and activations are computed layer by layer.

2. **Loss Calculation**
   - Compares the output with the actual target.
   - Computes error using a **loss function** (e.g., MSE, CrossEntropy).

3. **Backward Propagation**
   - Uses gradient descent and backpropagation to update weights.
   - Gradients flow backward from output to input layers.

4. **Optimization**
   - Updates weights to minimize the loss.
   - Common optimizers: **SGD**, **Adam**, **RMSprop**

---

## 🔥 Common Activation Functions

| Function       | Use Case                      | Formula                                     |
|----------------|-------------------------------|---------------------------------------------|
| `ReLU`         | Hidden layers (default)       | `f(x) = max(0, x)`                          |
| `Sigmoid`      | Binary classification output  | `f(x) = 1 / (1 + e^(-x))`                   |
| `Tanh`         | Can work better than sigmoid  | `f(x) = (e^x - e^-x) / (e^x + e^-x)`        |
| `Softmax`      | Multi-class classification    | Converts scores to probabilities            |

---

## 📂 Folder Structure (Sample)

