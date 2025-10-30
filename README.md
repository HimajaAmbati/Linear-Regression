Linear Regression

# 📈 Linear Regression — My First ML Model

This folder contains my work on **Linear Regression**, one of the most fundamental algorithms in Machine Learning.  
I implemented and explored it using the **House Price Prediction Dataset** from Kaggle.

---

## 🧠 What I Learned

### 📘 Concept
- Regression predicts **continuous values**.
- Linear Regression finds the **best-fitting line** that minimizes the error between actual and predicted outputs.

### ⚙️ Math Behind It
\[
\hat{y} = w_0 + w_1x_1 + w_2x_2 + ... + w_nx_n
\]
\[
\text{MSE} = \frac{1}{n}\sum_{i=1}^n (y_i - \hat{y_i})^2
\]

### 🔁 Training Method
- Implemented **Gradient Descent** manually to minimize the loss.
- Learned how **learning rate (α)** affects convergence.

### 🧩 Regularization
- Learned about **overfitting** and implemented:
  - **Ridge Regression (L2 penalty)**  
  - **Lasso Regression (L1 penalty)**

---

## 💻 Code & Implementation

- I used **Google Colab** for experimentation.
- My notebook covers:
  - Linear Regression (from scratch)
  - Linear Regression (using `scikit-learn`)
  - Regularization techniques (Ridge, Lasso)
  - Visualization (Actual vs Predicted, Residuals, Heatmap)

---

## 📊 Evaluation Metrics
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

---

## 🧩 Visualization Examples
- Best-fit line between area and price  
- Residual error plots  

---

## 🧠 Key Takeaways
- Understood the math behind **Linear Regression**.
- Learned to implement ML logic **from scratch** and compare with **library results**.
- Understood the role of **regularization** in avoiding overfitting

**Author:** *Ambati Lakshmi Himaja*  
📅 *Part of my “Learning ML” series*  

