# 📘 Linear Regression from Scratch – Colab Notebook

A simple implementation of **Linear Regression** using just **NumPy**, written in Python and hosted on **Google Colab** ☁️.  
Perfect for understanding the basics of machine learning and how linear models work under the hood.

---

## 📌 What's Inside?

- 📊 Pure Python + NumPy implementation
- 🧠 Gradient Descent-based training
- 📉 Visualization of predictions
- 💡 Great for learning ML fundamentals

---

## 🧮 The Math

We aim to fit a linear model:


ŷ = w * x + b



Where:
- `ŷ` is the predicted output
- `w` is the weight (slope)
- `b` is the bias (intercept)

---

### 🎯 Loss Function (Mean Squared Error)

J(w, b) = (1/n) * Σ (ŷᵢ - yᵢ)²

Where:
- `n` is the number of data points
- `ŷᵢ` is the predicted value
- `yᵢ` is the actual value

---

### 🔁 Gradient Descent Updates

w = w - α * ∂J/∂w
b = b - α * ∂J/∂b


Where `α` is the learning rate.


---

## ▶️ Try it on Colab

Click below to open the notebook in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/CraftyEngineer/Linear-Regression-From-Scratch/blob/main/linear-regression-from-scratch.ipynb)

---

## 🧑‍💻 Author

Made with ❤️ by [CraftyEngineer](https://github.com/CraftyEngineer)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
