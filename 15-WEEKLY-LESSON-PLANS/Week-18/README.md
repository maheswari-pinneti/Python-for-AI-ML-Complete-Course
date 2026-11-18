# Week 18 – Model Evaluation and Optimization

> **Phase:** Phase 6 – Advanced Machine Learning  
> **Duration:** 6 Days (1 Hour / Day = 6 Hours Total)  
> **Course Framework:** 144 Hours – Python for AI/ML Complete Course  

---

## 📌 Weekly Overview

Welcome to **Week 18** of the **Python for AI/ML** curriculum. In this module, students focus on **Model Evaluation and Optimization** within **Phase 6 – Advanced Machine Learning**. The curriculum is structured with a progressive 6-day daily pedagogy: starting with conceptual grounding, moving to syntax and coding, exploring practical examples, deepening through advanced concepts and real-world applications, and culminating in hands-on exercises and weekly assessment on Day 6.

---

## 📅 Daily Teaching Schedule

| Day | Topic | Teaching Approach | Core Focus / Deliverable |
| :--- | :--- | :--- | :--- |
| **Day 1** | Model Evaluation Fundamentals | *Concepts and theory* | Why evaluation methodology determines real-world model success |
| **Day 2** | Confusion Matrix, Accuracy, Precision and Recall | *Syntax and coding* | Anatomy of the Confusion Matrix: TP, TN, FP (Type I), FN (Type II) |
| **Day 3** | F1-Score, ROC Curve and AUC | *Practical examples* | Harmonic mean of precision and recall: $F_1 = 2 \times \frac{P \times R}{P + R}$ |
| **Day 4** | Cross-Validation and Hyperparameter Tuning | *Advanced concepts* | K-Fold Cross-Validation and Stratified K-Fold for classification (`cross_val_score`) |
| **Day 5** | Overfitting, Underfitting, Regularization and Ensemble Learning | *Real-world applications* | Regularization techniques: L1 (Lasso) for sparsity, L2 (Ridge) for weight shrinkage, ElasticNet |
| **Day 6** | Model Optimization Practical Project | *Exercises, assignments and weekly assessment* | End-to-end model optimization challenge on an imbalanced classification problem |

---

## 📖 Detailed Daily Lesson Plans

### 🗓️ Day 1: Model Evaluation Fundamentals
- **Teaching Approach:** `Concepts and theory`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Why evaluation methodology determines real-world model success
  - Limitations of simple train/test split: variance in small datasets
  - The Bias-Variance Tradeoff: Underfitting (High Bias) vs Overfitting (High Variance)
  - Learning curves: diagnosing model capacity and data sufficiency
- **Hands-on / Practical Implementation:**
  - Conceptual walkthrough with architectural whiteboard / markdown notes, live code demonstration of primary concepts, and Q&A on fundamental principles.

### 🗓️ Day 2: Confusion Matrix, Accuracy, Precision and Recall
- **Teaching Approach:** `Syntax and coding`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Anatomy of the Confusion Matrix: TP, TN, FP (Type I), FN (Type II)
  - Why accuracy is misleading on imbalanced datasets
  - Precision: $\frac{TP}{TP + FP}$ (minimizing false positives)
  - Recall (Sensitivity): $\frac{TP}{TP + FN}$ (minimizing false negatives) and business tradeoffs
- **Hands-on / Practical Implementation:**
  - Live coding session in VS Code / Jupyter Notebook demonstrating exact syntax, common error handling, and core code execution.

### 🗓️ Day 3: F1-Score, ROC Curve and AUC
- **Teaching Approach:** `Practical examples`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Harmonic mean of precision and recall: $F_1 = 2 \times \frac{P \times R}{P + R}$
  - Macro, Micro, and Weighted F1-scores for multi-class classification
  - ROC (Receiver Operating Characteristic) curve: TPR vs FPR across thresholds
  - AUC (Area Under the ROC Curve): interpretation and threshold tuning
- **Hands-on / Practical Implementation:**
  - Step-by-step practical coding of realistic scenarios, comparative examples, and interactive coding exercises for students.

### 🗓️ Day 4: Cross-Validation and Hyperparameter Tuning
- **Teaching Approach:** `Advanced concepts`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - K-Fold Cross-Validation and Stratified K-Fold for classification (`cross_val_score`)
  - Time-series split for sequential data
  - Grid Search: exhaustive search with `GridSearchCV`
  - Randomized Search: efficient sampling with `RandomizedSearchCV`
- **Hands-on / Practical Implementation:**
  - Deep dive into inner mechanics, optimization techniques, edge cases, and best practice design patterns.

### 🗓️ Day 5: Overfitting, Underfitting, Regularization and Ensemble Learning
- **Teaching Approach:** `Real-world applications`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Regularization techniques: L1 (Lasso) for sparsity, L2 (Ridge) for weight shrinkage, ElasticNet
  - Early stopping principles and pruning
  - Ensemble learning: Boosting vs Bagging vs Stacking (`VotingClassifier`, `StackingClassifier`)
  - Introduction to gradient boosted trees: XGBoost and LightGBM fundamentals
- **Hands-on / Practical Implementation:**
  - End-to-end implementation of an industry-relevant mini-project or case study showing how these skills power AI/ML pipelines.

### 🗓️ Day 6: Model Optimization Practical Project
- **Teaching Approach:** `Exercises, assignments and weekly assessment`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - End-to-end model optimization challenge on an imbalanced classification problem
  - Pipeline integration with hyperparameter tuning and cross-validation
  - Threshold moving to optimize business metric (cost matrix)
  - Weekly assessment: Model tuning submission, metrics report, and optimization quiz
- **Hands-on / Practical Implementation:**
  - Guided lab review, live troubleshooting of assignment problems, timed coding challenge, and weekly assessment grading.

---

## 🎯 Weekly Assessment & Deliverables (Day 6)

At the conclusion of **Week 18**, each student is required to complete and submit the following:
1. **Coding Exercises:** Complete all daily coding tasks and store them in the respective practice files.
2. **Weekly Assessment Challenge:** Complete the designated practical assignment on **Model Evaluation and Optimization**.
3. **Code Quality Review:** Ensure code adheres to PEP 8 standards, includes clean comments, and avoids anti-patterns.
4. **Knowledge Check:** Complete the short theoretical evaluation covering key terminology and design decisions.

---

## 💡 Pedagogical Notes for Instructors

> **Important Guidance:** This is part of an intensive 144-hour curriculum. Prioritize student progress, keyboard time, and hands-on coding capability over pure passive theory. Ensure every student types out the code and sees it execute successfully.
