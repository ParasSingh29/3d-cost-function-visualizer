# 3D Cost Function Visualization

A clean, interactive 3D visualization of a parabolic "soup bowl" cost function surface landscape built using Python, NumPy, and Matplotlib. This project demonstrates how optimization algorithms navigate a machine learning weight-and-bias parameter space to minimize total cost.

## 📊 The Visualization

<img width="831" height="655" alt="image" src="https://github.com/user-attachments/assets/506dab61-e9aa-41d9-9fc1-1e390628847c" />


## 🛠️ How It Works

The script builds a standard coordinate coordinate grid mapping weights ($w$) and biases ($b$) across a customized parameter range. It evaluates the surface elevation using a classic squared optimization formula:

$$Z = W^2 + B^2$$

The gradient transitions dynamically from dark purple (minimum cost) up to bright yellow (maximum cost), providing a clean visual map of the error landscape.

## 🚀 Built With
* **Python** 
* **Google Colab** (Cloud Jupyter Notebook Environment)
* **NumPy** - Matrix grid calculations
* **Matplotlib** - 3D data engine rendering
