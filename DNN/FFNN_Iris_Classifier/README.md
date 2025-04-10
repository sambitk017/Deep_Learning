# 🌸 Deep Neural Network on Iris Dataset

This project demonstrates a basic **Feedforward Deep Neural Network (DNN)** implementation using the classic **Iris dataset**. The model is built using TensorFlow and Keras, and is aimed at multi-class classification of flower species based on sepal and petal dimensions.

---

## 📊 Dataset: Iris Flower Dataset

The **Iris dataset** is a well-known classification dataset that includes 150 samples of iris flowers from three species:
- *Iris setosa*
- *Iris versicolor*
- *Iris virginica*

Each sample contains **4 numerical features**:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

The dataset is **already cleaned and balanced**, making it ideal for training a baseline DNN.

---

## 🧠 Feedforward Neural Network (FFNN)

A **Feedforward Neural Network (FFNN)** is the simplest type of artificial neural network where connections between the nodes do not form a cycle. The information moves in only one direction—from input to output.

### 📌 Key Components:

#### ✅ Layers
- **Input Layer**: Receives the input features (in this case, 4 features).
- **Hidden Layers**: Consist of fully connected (dense) layers with non-linear activation functions.
- **Output Layer**: Outputs the prediction probabilities for each class using the **softmax** function (3 classes).

#### 🔄 Phases in FFNN
1. **Forward Propagation**: Data flows through the network from input to output.
2. **Loss Calculation**: Error is calculated using a loss function like categorical crossentropy.
3. **Backward Propagation**: Gradients are calculated and propagated back to update weights.
4. **Optimization**: Weights are optimized using an algorithm like **Adam** or **SGD**.

---

## ⚙️ Activation Functions Used

- **ReLU (Rectified Linear Unit)**: Used in hidden layers to introduce non-linearity.
- **Softmax**: Used in the output layer to produce a probability distribution over classes.
