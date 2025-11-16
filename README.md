# 📉 Linear Regression from Scratch: Gradient Descent

This repository contains my first implementation of a fundamental machine learning algorithm: **Simple Linear Regression** solved using the **Batch Gradient Descent** optimization technique. The model predicts salary based on years of experience.

---
## 🎯 Goal

The primary goal of this project was to implement the following core components without relying on high-level libraries (like Scikit-learn):

* **Hypothesis Function:** f_{w,b}(x) = w*x + b
* **Cost Function:** J(w, b) = \frac{1}{2m} \sum_{i=1}^{m} (f_wb - y^{(i)})^2
* **Gradient Descent:** Iteratively updating parameters w and b to minimize J(w, b).

## ⚙️ Model Parameters

After 10,000 iterations with a learning rate of 0.01, the final parameters found were:
* **Weight (w):** `9449.962325379338` (Represents the estimated salary increase per year of experience.)
* **Bias (b):** `24848.203939785166` (Represents the starting salary/intercept.)

---
## 💻 How to Run the Code

### Prerequisites

You need the following Python libraries installed:

* Python 3.x
* **Pandas** (for reading the CSV file)
* **NumPy** (for numerical operations like `np.arange`)
* **Matplotlib** (for plotting the cost function and the final regression line)

### Installation

You can install the required libraries using pip:
```bash
pip install pandas numpy matplotlib
