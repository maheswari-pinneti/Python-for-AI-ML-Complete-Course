# Week 19 – Neural Network Fundamentals

> **Phase:** Phase 7 – Deep Learning  
> **Duration:** 6 Days (1 Hour / Day = 6 Hours Total)  
> **Course Framework:** 144 Hours – Python for AI/ML Complete Course  

---

## 📌 Weekly Overview

Welcome to **Week 19** of the **Python for AI/ML** curriculum. In this module, students focus on **Neural Network Fundamentals** within **Phase 7 – Deep Learning**. The curriculum is structured with a progressive 6-day daily pedagogy: starting with conceptual grounding, moving to syntax and coding, exploring practical examples, deepening through advanced concepts and real-world applications, and culminating in hands-on exercises and weekly assessment on Day 6.

---

## 📅 Daily Teaching Schedule

| Day | Topic | Teaching Approach | Core Focus / Deliverable |
| :--- | :--- | :--- | :--- |
| **Day 1** | Introduction to Deep Learning | *Concepts and theory* | What is Deep Learning and why now? (Compute, data, architectural breakthroughs) |
| **Day 2** | Artificial Neural Networks and Perceptrons | *Syntax and coding* | The Rosenblatt Perceptron: inputs, weights, bias, linear combination $z = \mathbf{w}^T \mathbf{x} + b$ |
| **Day 3** | Activation Functions | *Practical examples* | Why non-linear activation functions are necessary for universal approximation |
| **Day 4** | Forward Propagation | *Advanced concepts* | Mathematical mechanics of forward propagation through multiple hidden layers |
| **Day 5** | Backpropagation and Gradient Descent | *Real-world applications* | The chain rule of calculus applied to computational graphs |
| **Day 6** | Build a Basic Neural Network | *Exercises, assignments and weekly assessment* | Implementing a 2-layer Neural Network from scratch using only NumPy |

---

## 📖 Detailed Daily Lesson Plans

### 🗓️ Day 1: Introduction to Deep Learning
- **Teaching Approach:** `Concepts and theory`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - What is Deep Learning and why now? (Compute, data, architectural breakthroughs)
  - Biological neuron vs Artificial neuron (McCulloch-Pitts model)
  - From shallow machine learning to hierarchical representation learning
  - Deep learning landscape: computer vision, NLP, speech, robotics, and generative models
- **Hands-on / Practical Implementation:**
  - Conceptual walkthrough with architectural whiteboard / markdown notes, live code demonstration of primary concepts, and Q&A on fundamental principles.

### 🗓️ Day 2: Artificial Neural Networks and Perceptrons
- **Teaching Approach:** `Syntax and coding`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - The Rosenblatt Perceptron: inputs, weights, bias, linear combination $z = \mathbf{w}^T \mathbf{x} + b$
  - Step activation function and limitation of single-layer perceptrons (the XOR problem)
  - Multi-Layer Perceptron (MLP) architecture: input layer, hidden layers, output layer
  - Dense (fully connected) layers and matrix representation of weights
- **Hands-on / Practical Implementation:**
  - Live coding session in VS Code / Jupyter Notebook demonstrating exact syntax, common error handling, and core code execution.

### 🗓️ Day 3: Activation Functions
- **Teaching Approach:** `Practical examples`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Why non-linear activation functions are necessary for universal approximation
  - Classic activations: Sigmoid and Tanh (and the vanishing gradient problem)
  - Modern activations: ReLU (Rectified Linear Unit), Leaky ReLU, ELU, GELU
  - Output layer activations: Softmax for multi-class, Sigmoid for binary classification
- **Hands-on / Practical Implementation:**
  - Step-by-step practical coding of realistic scenarios, comparative examples, and interactive coding exercises for students.

### 🗓️ Day 4: Forward Propagation
- **Teaching Approach:** `Advanced concepts`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Mathematical mechanics of forward propagation through multiple hidden layers
  - Matrix multiplication formulation: $Z^{[l]} = W^{[l]} A^{[l-1]} + b^{[l]}$, $A^{[l]} = g^{[l]}(Z^{[l]})$
  - Loss functions: Mean Squared Error (regression), Binary Cross-Entropy, Categorical Cross-Entropy
  - Computing loss across mini-batches of training examples
- **Hands-on / Practical Implementation:**
  - Deep dive into inner mechanics, optimization techniques, edge cases, and best practice design patterns.

### 🗓️ Day 5: Backpropagation and Gradient Descent
- **Teaching Approach:** `Real-world applications`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - The chain rule of calculus applied to computational graphs
  - Deriving gradients of loss with respect to weights and biases: $\frac{\partial L}{\partial W^{[l]}}$
  - Weight updates: Stochastic Gradient Descent (SGD), Mini-batch SGD
  - Modern optimizers overview: Momentum, RMSProp, Adam (Adaptive Moment Estimation)
- **Hands-on / Practical Implementation:**
  - End-to-end implementation of an industry-relevant mini-project or case study showing how these skills power AI/ML pipelines.

### 🗓️ Day 6: Build a Basic Neural Network
- **Teaching Approach:** `Exercises, assignments and weekly assessment`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Implementing a 2-layer Neural Network from scratch using only NumPy
  - Writing explicit forward pass, backward pass, and parameter update loop
  - Training the custom network to solve non-linear classification (e.g. XOR, circular data)
  - Weekly assessment: Neural network scratch implementation code review and quiz
- **Hands-on / Practical Implementation:**
  - Guided lab review, live troubleshooting of assignment problems, timed coding challenge, and weekly assessment grading.

---

## 🎯 Weekly Assessment & Deliverables (Day 6)

At the conclusion of **Week 19**, each student is required to complete and submit the following:
1. **Coding Exercises:** Complete all daily coding tasks and store them in the respective practice files.
2. **Weekly Assessment Challenge:** Complete the designated practical assignment on **Neural Network Fundamentals**.
3. **Code Quality Review:** Ensure code adheres to PEP 8 standards, includes clean comments, and avoids anti-patterns.
4. **Knowledge Check:** Complete the short theoretical evaluation covering key terminology and design decisions.

---

## 💡 Pedagogical Notes for Instructors

> **Important Guidance:** This is part of an intensive 144-hour curriculum. Prioritize student progress, keyboard time, and hands-on coding capability over pure passive theory. Ensure every student types out the code and sees it execute successfully.
