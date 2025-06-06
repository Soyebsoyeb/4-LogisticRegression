# (1) 📊 Logistic Regression Sigmoid Visualization

*A visual demonstration of how parameters affect classification in logistic regression*

## 🌐 Concept Overview
This visualization demonstrates the core mechanism of logistic regression through the sigmoid function:

def sigmoid(z):
    return 1/(1+np.exp(-z))  # S-shaped curve mapping ℝ → (0,1)





# (2) 📊 Interactive Logistic Regression Visualization

3D Sigmoid Surface with Dynamic Decision Boundary

Interactive Demo
(Screen recording of slider interaction and view changes)

🌟 Key Features
Real-time parameter control with interactive sliders

Synced 3D & 2D views of probability landscape

Animated transitions between parameter states

Multiple camera angles (top/side/reset views)

Hover tooltips showing exact probability values

Responsive design works on desktop/mobile

🧮 Mathematical Foundation
Core Equation
python
P(y=1) = σ(w₁x₁ + w₂x₂ + b) = 1/(1 + e⁻ᶻ)
Where:

σ = Sigmoid function
w₁, w₂ = Feature weights
b = Bias term
z = Decision boundary linear combination.





# (3) 📊 Logistic Regression Visualization with Sigmoid and Cross-Entropy Loss

This Python script visualizes logistic regression by plotting sigmoid functions for different parameters (`theta` and `theta0`) and computing the corresponding cross-entropy loss.
## Features
- Plots sigmoid functions for different parameter combinations
- Highlights data points on the x-axis (blue for class 1, red for class 0)
- Shows decision boundaries and model confidence via dotted green lines
- Computes and displays cross-entropy loss for each parameter set
- Clean 2×2 subplot layout for easy comparison

## Code Overview
import numpy as np
import matplotlib.pyplot as plt

# Data
x = np.array([1, 2, -1, 2])   # Features
y = np.array([1, 1, 0, 0])    # Binary labels

# Sigmoid and loss functions
def sigmoid(z): ...
def cross_entropy_loss(x, y, theta, theta0): ...

# Parameter sets to test
theta_values = [1, -1, 2, -2]
theta0_values = [0, 1, -1, 2]






# (4) 📊 2D Gradient Descent Visualization
 Gradient Descent Visualization on f(x) = x²

This Python script visually demonstrates gradient descent optimization on the quadratic function f(x) = x², showing each iteration's position, tangent line, and optimization path.

## Features

- 📉 **Step-by-step visualization** of gradient descent
- 📐 **Tangent line plotting** at each iteration
- 📊 **Interactive matplotlib figures** for each step
- 🔍 **Adjustable parameters**: learning rate, iterations, starting point
- 📈 **Clear visualization** of optimization trajectory

  



# (5) 📊 3D Gradient Descent Visualization

![gradient_descent](https://github.com/user-attachments/assets/afce4f84-1dab-437a-86b8-a0c939b2dd30)

This project visualizes gradient descent optimization on a 3D parabolic function (f(x,y) = x² + y²) using Matplotlib. It demonstrates how the algorithm navigates toward the minimum point through a series of interactive 3D plots.

## Features

- 🎥 **Animated 3D visualization** of gradient descent steps
- 📐 **Gradient vector visualization** showing descent direction
- 📊 **Interactive plots** with rotation/zoom capability
- 🖼️ **Frame-by-frame output** for detailed analysis
- 🎚️ **Adjustable parameters**: learning rate, iterations, starting point
- 🔄 **Multiple output formats**: GIF, HTML5, individual frames






#(6) 📊 Logistic Regression from Scratch

This repository contains a Python implementation of logistic regression from scratch using NumPy. The implementation includes gradient descent optimization and visualization of the decision boundary during training.

## Features

- Sigmoid activation function
- Binary cross-entropy (log loss) calculation
- Gradient descent optimization
- Interactive visualization of decision boundary evolution
- Handcrafted 2D dataset for binary classification

## Requirements

- Python 3.x
- NumPy
- Matplotlib




# (7) 📊 Logistic Regression with Polynomial Features

This project implements logistic regression with polynomial feature expansion to classify non-linearly separable data. The implementation includes gradient descent optimization and visualization of decision boundaries.

## Features

- Polynomial feature expansion up to any degree
- Logistic regression with gradient descent
- Decision boundary visualization
- Cost function tracking
- Regularization-ready structure (L1/L2 can be easily added)

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- Seaborn
- SciPy




# (8) 📊 Regularized Logistic Regression with Polynomial Features

Regularization is a crucial technique for preventing overfitting in machine learning models, particularly when dealing with:

- High-dimensional features (like polynomial expansions)
- Limited training data
- Noisy datasets

## Features
- **Polynomial Feature Expansion**: Up to degree `n` configurable
- **L2 Regularization**: Prevent overfitting with adjustable λ

