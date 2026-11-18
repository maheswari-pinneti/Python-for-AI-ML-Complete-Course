# Week 17 – Advanced ML and Feature Engineering

> **Phase:** Phase 6 – Advanced Machine Learning  
> **Duration:** 6 Days (1 Hour / Day = 6 Hours Total)  
> **Course Framework:** 144 Hours – Python for AI/ML Complete Course  

---

## 📌 Weekly Overview

Welcome to **Week 17** of the **Python for AI/ML** curriculum. In this module, students focus on **Advanced ML and Feature Engineering** within **Phase 6 – Advanced Machine Learning**. The curriculum is structured with a progressive 6-day daily pedagogy: starting with conceptual grounding, moving to syntax and coding, exploring practical examples, deepening through advanced concepts and real-world applications, and culminating in hands-on exercises and weekly assessment on Day 6.

---

## 📅 Daily Teaching Schedule

| Day | Topic | Teaching Approach | Core Focus / Deliverable |
| :--- | :--- | :--- | :--- |
| **Day 1** | Scikit-learn Architecture and Workflow | *Concepts and theory* | Consistent design principles: Estimators, Transformers, and Predictors |
| **Day 2** | Data Preprocessing and Scaling | *Syntax and coding* | Handling numeric features: `StandardScaler` (Z-score) vs `MinMaxScaler` (0 to 1) |
| **Day 3** | Feature Engineering | *Practical examples* | Creating domain-specific features (ratios, differences, aggregations) |
| **Day 4** | Feature Selection | *Advanced concepts* | Why feature selection matters: reducing overfitting, improving inference latency |
| **Day 5** | Pipelines and Column Transformers | *Real-world applications* | Building robust multi-step workflows using `Pipeline` from `sklearn.pipeline` |
| **Day 6** | End-to-End ML Pipeline Practice | *Exercises, assignments and weekly assessment* | Constructing a complete production-grade pipeline from raw dirty data to trained model |

---

## 📖 Detailed Daily Lesson Plans

### 🗓️ Day 1: Scikit-learn Architecture and Workflow
- **Teaching Approach:** `Concepts and theory`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Consistent design principles: Estimators, Transformers, and Predictors
  - The Scikit-learn unified API: `.fit()`, `.transform()`, `.fit_transform()`, `.predict()`
  - Writing clean, reproducible machine learning code workflows
  - Preventing data leakage between training and evaluation splits
- **Hands-on / Practical Implementation:**
  - Conceptual walkthrough with architectural whiteboard / markdown notes, live code demonstration of primary concepts, and Q&A on fundamental principles.

### 🗓️ Day 2: Data Preprocessing and Scaling
- **Teaching Approach:** `Syntax and coding`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Handling numeric features: `StandardScaler` (Z-score) vs `MinMaxScaler` (0 to 1)
  - `RobustScaler` for datasets with extreme outliers
  - Categorical encoding: `OneHotEncoder` (nominal) vs `OrdinalEncoder` / `LabelEncoder` (ordinal)
  - Handling rare categories and unknown values during inference
- **Hands-on / Practical Implementation:**
  - Live coding session in VS Code / Jupyter Notebook demonstrating exact syntax, common error handling, and core code execution.

### 🗓️ Day 3: Feature Engineering
- **Teaching Approach:** `Practical examples`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Creating domain-specific features (ratios, differences, aggregations)
  - Date-time feature extraction: year, month, day, day-of-week, is_weekend, quarter
  - Binning / discretization of continuous variables (`pd.cut()`, `pd.qcut()`)
  - Log and power transformations for skewed distributions (`np.log1p`, `PowerTransformer`)
- **Hands-on / Practical Implementation:**
  - Step-by-step practical coding of realistic scenarios, comparative examples, and interactive coding exercises for students.

### 🗓️ Day 4: Feature Selection
- **Teaching Approach:** `Advanced concepts`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Why feature selection matters: reducing overfitting, improving inference latency
  - Filter methods: VarianceThreshold, Correlation filters, ANOVA F-test, Mutual Information
  - Wrapper methods: Recursive Feature Elimination (RFE) with `sklearn.feature_selection.RFE`
  - Embedded methods: L1 regularization (Lasso) and tree-based feature importances
- **Hands-on / Practical Implementation:**
  - Deep dive into inner mechanics, optimization techniques, edge cases, and best practice design patterns.

### 🗓️ Day 5: Pipelines and Column Transformers
- **Teaching Approach:** `Real-world applications`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Building robust multi-step workflows using `Pipeline` from `sklearn.pipeline`
  - Transforming heterogeneous columns simultaneously with `ColumnTransformer`
  - Preventing data leakage automatically during cross-validation
  - Exporting and reusing production-ready preprocessing pipelines
- **Hands-on / Practical Implementation:**
  - End-to-end implementation of an industry-relevant mini-project or case study showing how these skills power AI/ML pipelines.

### 🗓️ Day 6: End-to-End ML Pipeline Practice
- **Teaching Approach:** `Exercises, assignments and weekly assessment`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Constructing a complete production-grade pipeline from raw dirty data to trained model
  - Testing inference on new unseen data batches with zero pipeline breakage
  - Custom transformers: writing a class extending `BaseEstimator` and `TransformerMixin`
  - Weekly assessment: 4 pipeline construction problems and evaluation rubric
- **Hands-on / Practical Implementation:**
  - Guided lab review, live troubleshooting of assignment problems, timed coding challenge, and weekly assessment grading.

---

## 🎯 Weekly Assessment & Deliverables (Day 6)

At the conclusion of **Week 17**, each student is required to complete and submit the following:
1. **Coding Exercises:** Complete all daily coding tasks and store them in the respective practice files.
2. **Weekly Assessment Challenge:** Complete the designated practical assignment on **Advanced ML and Feature Engineering**.
3. **Code Quality Review:** Ensure code adheres to PEP 8 standards, includes clean comments, and avoids anti-patterns.
4. **Knowledge Check:** Complete the short theoretical evaluation covering key terminology and design decisions.

---

## 💡 Pedagogical Notes for Instructors

> **Important Guidance:** This is part of an intensive 144-hour curriculum. Prioritize student progress, keyboard time, and hands-on coding capability over pure passive theory. Ensure every student types out the code and sees it execute successfully.
