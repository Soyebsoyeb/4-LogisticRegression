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
