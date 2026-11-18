# Week 14 – Regression Algorithms

> **Phase:** Phase 5 – Machine Learning Fundamentals  
> **Duration:** 6 Days (1 Hour / Day = 6 Hours Total)  
> **Course Framework:** 144 Hours – Python for AI/ML Complete Course  

---

## 📌 Weekly Overview

Welcome to **Week 14** of the **Python for AI/ML** curriculum. In this module, students focus on **Regression Algorithms** within **Phase 5 – Machine Learning Fundamentals**. The curriculum is structured with a progressive 6-day daily pedagogy: starting with conceptual grounding, moving to syntax and coding, exploring practical examples, deepening through advanced concepts and real-world applications, and culminating in hands-on exercises and weekly assessment on Day 6.

---

## 📅 Daily Teaching Schedule

| Day | Topic | Teaching Approach | Core Focus / Deliverable |
| :--- | :--- | :--- | :--- |
| **Day 1** | Introduction to Regression | *Concepts and theory* | Definition of regression and modeling relationships between variables |
| **Day 2** | Simple Linear Regression | *Syntax and coding* | Fitting Simple Linear Regression using `LinearRegression` from `sklearn.linear_model` |
| **Day 3** | Multiple Linear Regression | *Practical examples* | Extending to multiple predictor features: $y = w_1 x_1 + w_2 x_2 + \dots + b$ |
| **Day 4** | Logistic Regression | *Advanced concepts* | Why linear regression fails for binary classification problems |
| **Day 5** | Regression Metrics: MAE, MSE, RMSE and R² | *Real-world applications* | Mean Absolute Error (MAE): interpretability and robustness to outliers |
| **Day 6** | House Price Prediction Project | *Exercises, assignments and weekly assessment* | Building an end-to-end regression model to predict housing prices |

---

## 📖 Detailed Daily Lesson Plans

### 🗓️ Day 1: Introduction to Regression
- **Teaching Approach:** `Concepts and theory`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Definition of regression and modeling relationships between variables
  - The regression hypothesis function: $y = wx + b$ or $y = eta_0 + eta_1 x_1 + \dots$
  - Ordinary Least Squares (OLS) criterion: minimizing the sum of squared residuals
  - Assumptions of linear regression: linearity, independence, homoscedasticity, normality
- **Hands-on / Practical Implementation:**
  - Conceptual walkthrough with architectural whiteboard / markdown notes, live code demonstration of primary concepts, and Q&A on fundamental principles.

### 🗓️ Day 2: Simple Linear Regression
- **Teaching Approach:** `Syntax and coding`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Fitting Simple Linear Regression using `LinearRegression` from `sklearn.linear_model`
  - Extracting model parameters: `model.coef_` (slope) and `model.intercept_` (intercept)
  - Visualizing the best-fit regression line over training and test scatter points
  - Making individual and batch predictions on new feature values
- **Hands-on / Practical Implementation:**
  - Live coding session in VS Code / Jupyter Notebook demonstrating exact syntax, common error handling, and core code execution.

### 🗓️ Day 3: Multiple Linear Regression
- **Teaching Approach:** `Practical examples`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Extending to multiple predictor features: $y = w_1 x_1 + w_2 x_2 + \dots + b$
  - Interpreting feature coefficients and feature importance
  - Multicollinearity: understanding Variance Inflation Factor (VIF)
  - Polynomial Regression for non-linear data using `PolynomialFeatures`
- **Hands-on / Practical Implementation:**
  - Step-by-step practical coding of realistic scenarios, comparative examples, and interactive coding exercises for students.

### 🗓️ Day 4: Logistic Regression
- **Teaching Approach:** `Advanced concepts`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Why linear regression fails for binary classification problems
  - The Sigmoid activation function: $\sigma(z) = \frac{1}{1 + e^{-z}}$
  - Converting log-odds to probabilities ($0$ to $1$)
  - Binary Cross-Entropy (Log Loss) cost function and decision boundary
- **Hands-on / Practical Implementation:**
  - Deep dive into inner mechanics, optimization techniques, edge cases, and best practice design patterns.

### 🗓️ Day 5: Regression Metrics: MAE, MSE, RMSE and R²
- **Teaching Approach:** `Real-world applications`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Mean Absolute Error (MAE): interpretability and robustness to outliers
  - Mean Squared Error (MSE) and Root Mean Squared Error (RMSE): penalizing large errors
  - Coefficient of Determination ($R^2$ score) and Adjusted $R^2$
  - Computing metrics using `sklearn.metrics` (`mean_squared_error`, `r2_score`)
- **Hands-on / Practical Implementation:**
  - End-to-end implementation of an industry-relevant mini-project or case study showing how these skills power AI/ML pipelines.

### 🗓️ Day 6: House Price Prediction Project
- **Teaching Approach:** `Exercises, assignments and weekly assessment`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Building an end-to-end regression model to predict housing prices
  - Preprocessing features, training multiple regression models, and evaluating RMSE / $R^2$
  - Residual analysis plot to verify model assumptions
  - Weekly assessment: Project submission, code evaluation, and regression quiz
- **Hands-on / Practical Implementation:**
  - Guided lab review, live troubleshooting of assignment problems, timed coding challenge, and weekly assessment grading.

---

## 🎯 Weekly Assessment & Deliverables (Day 6)

At the conclusion of **Week 14**, each student is required to complete and submit the following:
1. **Coding Exercises:** Complete all daily coding tasks and store them in the respective practice files.
2. **Weekly Assessment Challenge:** Complete the designated practical assignment on **Regression Algorithms**.
3. **Code Quality Review:** Ensure code adheres to PEP 8 standards, includes clean comments, and avoids anti-patterns.
4. **Knowledge Check:** Complete the short theoretical evaluation covering key terminology and design decisions.

---

## 💡 Pedagogical Notes for Instructors

> **Important Guidance:** This is part of an intensive 144-hour curriculum. Prioritize student progress, keyboard time, and hands-on coding capability over pure passive theory. Ensure every student types out the code and sees it execute successfully.
