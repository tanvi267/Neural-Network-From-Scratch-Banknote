# Neural-Network-From-Scratch-Banknote
Neural Network Implementation from Scratch for Banknote Authentication

# 🧠 Neural Network From Scratch - Banknote Authentication

A simple **Feedforward Neural Network implemented from scratch in Python** for classifying banknotes as **Genuine or Forged**.

The project demonstrates the fundamental concepts of neural networks including **Forward Propagation, Backpropagation, Binary Cross-Entropy Loss, and Gradient Descent** without using deep learning frameworks such as TensorFlow or PyTorch.

---

## 🎯 Objective

The objective of this project is to implement and train a simple neural network from scratch using Python and NumPy for **binary classification** of banknotes.

---

## 📊 Dataset

The project uses the **Banknote Authentication Dataset**.

The dataset contains **1372 instances** and **4 numerical features**:

| Feature | Description |
|---|---|
| Variance | Variance of Wavelet Transformed Image |
| Skewness | Skewness of Wavelet Transformed Image |
| Curtosis | Curtosis of Wavelet Transformed Image |
| Entropy | Entropy of Wavelet Transformed Image |

### Target Variable

- `0` → Genuine Banknote
- `1` → Forged Banknote

**Problem Type:** Binary Classification

**Dataset Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/267/banknote+authentication)

---

## 🏗️ Neural Network Architecture

The neural network consists of three layers:

```text
             Input Layer
            4 Neurons
                │
                ▼
           Hidden Layer
            8 Neurons
              ReLU
                │
                ▼
           Output Layer
            1 Neuron
            Sigmoid
                │
                ▼
          Genuine / Forged

## ⚙️ Methodology

The neural network is trained using the following workflow:

| Step | Process                                     |
| ---: | ------------------------------------------- |
|  1️⃣ | Load the Banknote Authentication dataset    |
|  2️⃣ | Separate input features and target variable |
|  3️⃣ | Split data into training and testing sets   |
|  4️⃣ | Standardize the input features              |
|  5️⃣ | Initialize weights and biases               |
|  6️⃣ | Perform forward propagation                 |
|  7️⃣ | Calculate Binary Cross-Entropy loss         |
|  8️⃣ | Perform backpropagation                     |
|  9️⃣ | Update parameters using Gradient Descent    |
|   🔟 | Evaluate the trained model                  |

---

## 🔄 Neural Network Workflow

```text
                 📊 Input Dataset
                       │
                       ▼
              🔧 Data Preprocessing
                       │
                       ▼
              ➡️ Forward Propagation
                       │
                       ▼
                📉 Calculate Loss
                       │
                       ▼
              ⬅️ Backpropagation
                       │
                       ▼
              ⚡ Gradient Descent
                       │
                       ▼
                🔄 Update Weights
                       │
                       ▼
                  🎯 Prediction
```

---

## 🧮 Activation Functions

### ReLU

The **ReLU (Rectified Linear Unit)** activation function is used in the hidden layer.

```text
ReLU(x) = max(0, x)
```

It introduces non-linearity into the neural network and helps the model learn complex patterns.

### Sigmoid

The **Sigmoid** activation function is used in the output layer.

```text
Sigmoid(x) = 1 / (1 + e⁻ˣ)
```

It produces an output between **0 and 1**, making it suitable for binary classification.

---

## 📉 Loss Function

The model uses **Binary Cross-Entropy Loss** because the task is a binary classification problem.

The loss measures the difference between the actual labels and the predicted probabilities.

---

## 🚀 Optimization

The neural network is trained using **Gradient Descent**.

During training, the weights and biases are updated repeatedly to minimize the loss function.

```text
Prediction
    ↓
Calculate Error
    ↓
Compute Gradients
    ↓
Update Weights & Biases
    ↓
Repeat
```

---

## 🛠️ Technologies Used

| Technology      | Purpose                           |
| --------------- | --------------------------------- |
| 🐍 Python       | Programming Language              |
| 🔢 NumPy        | Neural Network calculations       |
| 🐼 Pandas       | Dataset handling                  |
| 📊 Matplotlib   | Data visualization                |
| 📓 Google Colab | Development environment           |
| 🐙 GitHub       | Version control & project hosting |

---

## 📈 Results

The trained neural network is evaluated using the test dataset.

### 🎯 Test Accuracy

> **Test Accuracy: `XX.XX%`**

The actual accuracy will be added after completing the model training and evaluation.

### 📉 Training Performance

The training loss is visualized using a **Loss vs Epochs** graph.

![Training Loss](screenshots/loss_curve.png)

### 🎯 Model Prediction

The model's prediction results are shown below:

![Model Accuracy](screenshots/accuracy_result.png)

---

## 📁 Project Structure

```text
Neural-Network-From-Scratch-Banknote/
│
├── 📁 dataset/
│   └── 📄 banknote_authentication.csv
│
├── 📁 screenshots/
│   ├── 🖼️ loss_curve.png
│   └── 🖼️ accuracy_result.png
│
├── 📓 Tanvi_GenerativeAILabAssignment.ipynb
│
└── 📄 README.md
```

---

## ✨ Key Features

* ✅ Neural Network implemented from scratch
* ✅ No TensorFlow or PyTorch
* ✅ Forward Propagation
* ✅ Backpropagation
* ✅ Gradient Descent
* ✅ ReLU Activation
* ✅ Sigmoid Activation
* ✅ Binary Cross-Entropy Loss
* ✅ Training Loss Visualization
* ✅ Binary Classification

---

## 📝 Conclusion

This project demonstrates the fundamental working of a **Feedforward Neural Network** by implementing its major components from scratch.

The model performs binary classification on the **Banknote Authentication Dataset** using forward propagation, backpropagation, Binary Cross-Entropy loss, and Gradient Descent.

---

## 👨‍💻 Author

**Name:** TANVI
**PRN:** 202401110010
**Course:** Generative AI Lab
**Department:** CSE AIML

---

⭐ **Neural Network From Scratch | Banknote Authentication**
