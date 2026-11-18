# Week 10 – NumPy

> **Phase:** Phase 4 – Data Analytics and Data Science  
> **Duration:** 6 Days (1 Hour / Day = 6 Hours Total)  
> **Course Framework:** 144 Hours – Python for AI/ML Complete Course  

---

## 📌 Weekly Overview

Welcome to **Week 10** of the **Python for AI/ML** curriculum. In this module, students focus on **NumPy** within **Phase 4 – Data Analytics and Data Science**. The curriculum is structured with a progressive 6-day daily pedagogy: starting with conceptual grounding, moving to syntax and coding, exploring practical examples, deepening through advanced concepts and real-world applications, and culminating in hands-on exercises and weekly assessment on Day 6.

---

## 📅 Daily Teaching Schedule

| Day | Topic | Teaching Approach | Core Focus / Deliverable |
| :--- | :--- | :--- | :--- |
| **Day 1** | Introduction to NumPy and Installation | *Concepts and theory* | What is NumPy and why is it faster than standard Python lists (C-contiguous arrays) |
| **Day 2** | NumPy Arrays and Array Creation | *Syntax and coding* | Creating 1D, 2D, and 3D arrays from lists (`np.array()`) |
| **Day 3** | Array Indexing, Slicing and Reshaping | *Practical examples* | 1D and 2D slicing syntax (`arr[row_start:row_stop, col_start:col_stop]`) |
| **Day 4** | Array Operations and Broadcasting | *Advanced concepts* | Element-wise arithmetic: `+`, `-`, `*`, `/`, `**` |
| **Day 5** | Mathematical and Statistical Functions | *Real-world applications* | Universal functions (ufuncs): `np.exp()`, `np.log()`, `np.sqrt()`, `np.abs()` |
| **Day 6** | NumPy Practical Programs and Exercises | *Exercises, assignments and weekly assessment* | Normalizing a feature dataset using Min-Max and Z-score with NumPy |

---

## 📖 Detailed Daily Lesson Plans

### 🗓️ Day 1: Introduction to NumPy and Installation
- **Teaching Approach:** `Concepts and theory`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - What is NumPy and why is it faster than standard Python lists (C-contiguous arrays)
  - Memory efficiency, vectorized operations, and SIMD hardware acceleration
  - Installing NumPy (`pip install numpy`) and convention (`import numpy as np`)
  - Understanding the `ndarray` object structure, `shape`, `dtype`, `ndim`, and `size`
- **Hands-on / Practical Implementation:**
  - Conceptual walkthrough with architectural whiteboard / markdown notes, live code demonstration of primary concepts, and Q&A on fundamental principles.

### 🗓️ Day 2: NumPy Arrays and Array Creation
- **Teaching Approach:** `Syntax and coding`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Creating 1D, 2D, and 3D arrays from lists (`np.array()`)
  - Specialized creation routines: `np.zeros()`, `np.ones()`, `np.full()`, `np.empty()`
  - Range and sequence arrays: `np.arange()` and `np.linspace()`
  - Random array generation: `np.random.rand()`, `randn()`, `randint()`, setting seeds (`np.random.seed`)
- **Hands-on / Practical Implementation:**
  - Live coding session in VS Code / Jupyter Notebook demonstrating exact syntax, common error handling, and core code execution.

### 🗓️ Day 3: Array Indexing, Slicing and Reshaping
- **Teaching Approach:** `Practical examples`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - 1D and 2D slicing syntax (`arr[row_start:row_stop, col_start:col_stop]`)
  - Views vs Copies in NumPy (`.copy()` vs memory view)
  - Boolean masking and filtering (`arr[arr > 5]`)
  - Reshaping arrays: `.reshape()`, `.flatten()`, `.ravel()`, `np.newaxis`
- **Hands-on / Practical Implementation:**
  - Step-by-step practical coding of realistic scenarios, comparative examples, and interactive coding exercises for students.

### 🗓️ Day 4: Array Operations and Broadcasting
- **Teaching Approach:** `Advanced concepts`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Element-wise arithmetic: `+`, `-`, `*`, `/`, `**`
  - NumPy Broadcasting rules: dimension compatibility and trailing axis matching
  - Matrix operations: dot product (`np.dot()`, `@`), matrix multiplication (`np.matmul()`)
  - Array stacking and splitting: `np.vstack()`, `np.hstack()`, `np.concatenate()`
- **Hands-on / Practical Implementation:**
  - Deep dive into inner mechanics, optimization techniques, edge cases, and best practice design patterns.

### 🗓️ Day 5: Mathematical and Statistical Functions
- **Teaching Approach:** `Real-world applications`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Universal functions (ufuncs): `np.exp()`, `np.log()`, `np.sqrt()`, `np.abs()`
  - Aggregation functions: `np.sum()`, `mean()`, `std()`, `var()`, `min()`, `max()` along axes (`axis=0`, `axis=1`)
  - Finding indices: `np.argmin()`, `np.argmax()`, `np.where()`
  - Linear algebra module: `np.linalg.inv()`, `np.linalg.det()`, `np.linalg.eig()`
- **Hands-on / Practical Implementation:**
  - End-to-end implementation of an industry-relevant mini-project or case study showing how these skills power AI/ML pipelines.

### 🗓️ Day 6: NumPy Practical Programs and Exercises
- **Teaching Approach:** `Exercises, assignments and weekly assessment`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Normalizing a feature dataset using Min-Max and Z-score with NumPy
  - Simulating random walks and Monte Carlo simulations
  - Building image filters or pixel manipulation using 3D NumPy arrays
  - Weekly assessment: 6 NumPy array manipulation and computation challenges
- **Hands-on / Practical Implementation:**
  - Guided lab review, live troubleshooting of assignment problems, timed coding challenge, and weekly assessment grading.

---

## 🎯 Weekly Assessment & Deliverables (Day 6)

At the conclusion of **Week 10**, each student is required to complete and submit the following:
1. **Coding Exercises:** Complete all daily coding tasks and store them in the respective practice files.
2. **Weekly Assessment Challenge:** Complete the designated practical assignment on **NumPy**.
3. **Code Quality Review:** Ensure code adheres to PEP 8 standards, includes clean comments, and avoids anti-patterns.
4. **Knowledge Check:** Complete the short theoretical evaluation covering key terminology and design decisions.

---

## 💡 Pedagogical Notes for Instructors

> **Important Guidance:** This is part of an intensive 144-hour curriculum. Prioritize student progress, keyboard time, and hands-on coding capability over pure passive theory. Ensure every student types out the code and sees it execute successfully.
