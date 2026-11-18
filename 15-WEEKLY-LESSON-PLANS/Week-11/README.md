# Week 11 – Pandas

> **Phase:** Phase 4 – Data Analytics and Data Science  
> **Duration:** 6 Days (1 Hour / Day = 6 Hours Total)  
> **Course Framework:** 144 Hours – Python for AI/ML Complete Course  

---

## 📌 Weekly Overview

Welcome to **Week 11** of the **Python for AI/ML** curriculum. In this module, students focus on **Pandas** within **Phase 4 – Data Analytics and Data Science**. The curriculum is structured with a progressive 6-day daily pedagogy: starting with conceptual grounding, moving to syntax and coding, exploring practical examples, deepening through advanced concepts and real-world applications, and culminating in hands-on exercises and weekly assessment on Day 6.

---

## 📅 Daily Teaching Schedule

| Day | Topic | Teaching Approach | Core Focus / Deliverable |
| :--- | :--- | :--- | :--- |
| **Day 1** | Introduction to Pandas and Series | *Concepts and theory* | What is Pandas and its role in the Data Science lifecycle |
| **Day 2** | DataFrames and DataFrame Creation | *Syntax and coding* | The Pandas `DataFrame`: 2D labeled tabular data structure |
| **Day 3** | Data Selection, Filtering and Sorting | *Practical examples* | Column selection: single column (Series) vs multiple columns (DataFrame) |
| **Day 4** | Handling Missing Values and Duplicates | *Advanced concepts* | Identifying missing data: `.isna()`, `.isnull()`, `.sum()` count of nulls |
| **Day 5** | Grouping, Merging, Joining and Aggregation | *Real-world applications* | Split-Apply-Combine pattern using `.groupby()` |
| **Day 6** | Pandas Data Analysis Project | *Exercises, assignments and weekly assessment* | End-to-end data exploration project on a real-world dataset (e.g., Titanic, Superstore Sales) |

---

## 📖 Detailed Daily Lesson Plans

### 🗓️ Day 1: Introduction to Pandas and Series
- **Teaching Approach:** `Concepts and theory`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - What is Pandas and its role in the Data Science lifecycle
  - Installing Pandas (`pip install pandas`) and convention (`import pandas as pd`)
  - The Pandas `Series`: 1D labeled array, index labels, and data types
  - Creating Series from lists, dictionaries, and scalar values
- **Hands-on / Practical Implementation:**
  - Conceptual walkthrough with architectural whiteboard / markdown notes, live code demonstration of primary concepts, and Q&A on fundamental principles.

### 🗓️ Day 2: DataFrames and DataFrame Creation
- **Teaching Approach:** `Syntax and coding`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - The Pandas `DataFrame`: 2D labeled tabular data structure
  - Creating DataFrames from dictionaries, lists of dictionaries, and 2D NumPy arrays
  - Reading external data: `pd.read_csv()`, `pd.read_excel()`, `pd.read_json()`
  - Initial inspection methods: `.head()`, `.tail()`, `.info()`, `.describe()`, `.shape`, `.dtypes`
- **Hands-on / Practical Implementation:**
  - Live coding session in VS Code / Jupyter Notebook demonstrating exact syntax, common error handling, and core code execution.

### 🗓️ Day 3: Data Selection, Filtering and Sorting
- **Teaching Approach:** `Practical examples`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Column selection: single column (Series) vs multiple columns (DataFrame)
  - Label-based indexing with `.loc[]` vs integer-based indexing with `.iloc[]`
  - Conditional filtering with Boolean indexing (e.g. `df[(df['age'] > 25) & (df['salary'] > 50000)]`)
  - Sorting data: `.sort_values()` by one or more columns, `.sort_index()`
- **Hands-on / Practical Implementation:**
  - Step-by-step practical coding of realistic scenarios, comparative examples, and interactive coding exercises for students.

### 🗓️ Day 4: Handling Missing Values and Duplicates
- **Teaching Approach:** `Advanced concepts`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Identifying missing data: `.isna()`, `.isnull()`, `.sum()` count of nulls
  - Dropping missing values: `.dropna(axis=0/1, how='any'/'all', thresh=...)`
  - Imputing missing values: `.fillna()` with mean, median, mode, forward fill (`ffill`)
  - Detecting and removing duplicate rows: `.duplicated()`, `.drop_duplicates()`
- **Hands-on / Practical Implementation:**
  - Deep dive into inner mechanics, optimization techniques, edge cases, and best practice design patterns.

### 🗓️ Day 5: Grouping, Merging, Joining and Aggregation
- **Teaching Approach:** `Real-world applications`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Split-Apply-Combine pattern using `.groupby()`
  - Aggregation functions: `.agg(['mean', 'std', 'count'])`
  - Merging DataFrames: `pd.merge()` (inner, left, right, outer joins)
  - Concatenation: `pd.concat()` along rows and columns, pivot tables with `df.pivot_table()`
- **Hands-on / Practical Implementation:**
  - End-to-end implementation of an industry-relevant mini-project or case study showing how these skills power AI/ML pipelines.

### 🗓️ Day 6: Pandas Data Analysis Project
- **Teaching Approach:** `Exercises, assignments and weekly assessment`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - End-to-end data exploration project on a real-world dataset (e.g., Titanic, Superstore Sales)
  - Cleaning dirty columns, converting datatypes, and engineering summary metrics
  - Exporting cleaned data: `.to_csv()`, `.to_json()`
  - Weekly assessment: Real-world data analysis task with evaluation rubric
- **Hands-on / Practical Implementation:**
  - Guided lab review, live troubleshooting of assignment problems, timed coding challenge, and weekly assessment grading.

---

## 🎯 Weekly Assessment & Deliverables (Day 6)

At the conclusion of **Week 11**, each student is required to complete and submit the following:
1. **Coding Exercises:** Complete all daily coding tasks and store them in the respective practice files.
2. **Weekly Assessment Challenge:** Complete the designated practical assignment on **Pandas**.
3. **Code Quality Review:** Ensure code adheres to PEP 8 standards, includes clean comments, and avoids anti-patterns.
4. **Knowledge Check:** Complete the short theoretical evaluation covering key terminology and design decisions.

---

## 💡 Pedagogical Notes for Instructors

> **Important Guidance:** This is part of an intensive 144-hour curriculum. Prioritize student progress, keyboard time, and hands-on coding capability over pure passive theory. Ensure every student types out the code and sees it execute successfully.
