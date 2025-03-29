## SGD Classifier from Scratch (with Log Loss and L2 Regularization)

This repository contains a step-by-step implementation of a **Stochastic Gradient Descent (SGD) Classifier** using **Log Loss** (Binary Cross Entropy) and **L2 Regularization**, written from scratch in Python using NumPy—without using Scikit-learn's model implementation.

### 📌 Objectives

- Implement logistic regression with SGD training from scratch.
- Use Log Loss as the objective function.
- Apply L2 regularization for weight penalty.
- Train and validate the model on a synthetic binary classification dataset.
- Compare performance against Scikit-learn's `SGDClassifier`.

---

### 📂 Project Structure

| File | Description |
|------|-------------|
| `SGC Logistic.ipynb` | Jupyter notebook containing full implementation, explanations, and visualization of training & testing performance. |

---

### ⚙️ What’s Implemented?

- ✅ Custom weight and bias initialization  
- ✅ Sigmoid activation function  
- ✅ Log Loss function  
- ✅ Per-sample SGD weight & bias gradient updates  
- ✅ L2 regularization during gradient descent  
- ✅ Model training loop with learning rate and alpha  
- ✅ Accuracy comparison with Scikit-learn's `SGDClassifier`  
- ✅ Loss plot (Epoch vs Train/Test loss)

---

### 📈 Results

- Achieved ~95% training and testing accuracy on synthetic data.
- Closely matches Scikit-learn's classifier weights and intercepts (difference < 1e-3).
- Visualized convergence of training and test loss over epochs.

---

### 🛠️ Tech Stack

- **Language**: Python 3  
- **Libraries**: NumPy, Matplotlib, Seaborn, Scikit-learn (only for data generation & comparison)

---

### 📊 Sample Output

```bash
Train Accuracy: 95.2%
Test Accuracy : 94.99%
```

---

### 🚀 How to Run

1. Clone the repository
2. Open `SGC Logistic.ipynb` using Jupyter Notebook or Google Colab
3. Run all cells step-by-step to follow the implementation and observe the results.

---

### 🧩 Learning Outcome

This project provides a practical understanding of how **logistic regression with SGD and regularization** works under the hood, and how it compares to high-level ML libraries like Scikit-learn.

---

Let me know if you want this turned into a `README.md` file or want badges, installation instructions, or a license added!
