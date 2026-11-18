# Week 23 – Model Deployment and MLOps

> **Phase:** Phase 9 – Deployment and MLOps  
> **Duration:** 6 Days (1 Hour / Day = 6 Hours Total)  
> **Course Framework:** 144 Hours – Python for AI/ML Complete Course  

---

## 📌 Weekly Overview

Welcome to **Week 23** of the **Python for AI/ML** curriculum. In this module, students focus on **Model Deployment and MLOps** within **Phase 9 – Deployment and MLOps**. The curriculum is structured with a progressive 6-day daily pedagogy: starting with conceptual grounding, moving to syntax and coding, exploring practical examples, deepening through advanced concepts and real-world applications, and culminating in hands-on exercises and weekly assessment on Day 6.

---

## 📅 Daily Teaching Schedule

| Day | Topic | Teaching Approach | Core Focus / Deliverable |
| :--- | :--- | :--- | :--- |
| **Day 1** | Git, GitHub and Project Version Control | *Concepts and theory* | Version control principles in collaborative software and AI engineering |
| **Day 2** | Flask and FastAPI Fundamentals | *Syntax and coding* | Web frameworks for machine learning: Flask vs FastAPI |
| **Day 3** | REST APIs and Model Integration | *Practical examples* | Designing RESTful endpoints for ML prediction (`POST /predict`) |
| **Day 4** | Streamlit Application Development | *Advanced concepts* | Introduction to Streamlit: rapid interactive web UI development in pure Python |
| **Day 5** | Docker and Cloud Deployment Introduction | *Real-world applications* | What is containerization and why 'it works on my machine' fails in production |
| **Day 6** | Model Serialization, Monitoring and MLOps Fundamentals | *Exercises, assignments and weekly assessment* | Model serialization formats: Pickle, Joblib, ONNX (Open Neural Network Exchange) |

---

## 📖 Detailed Daily Lesson Plans

### 🗓️ Day 1: Git, GitHub and Project Version Control
- **Teaching Approach:** `Concepts and theory`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Version control principles in collaborative software and AI engineering
  - Git workflow: repository setup, `git status`, `add`, `commit`, `branch`, `merge`
  - Remote repositories on GitHub: pushing, pulling, handling pull requests and code review
  - Creating effective `.gitignore` files for AI/ML projects (ignoring models, virtual environments, data)
- **Hands-on / Practical Implementation:**
  - Conceptual walkthrough with architectural whiteboard / markdown notes, live code demonstration of primary concepts, and Q&A on fundamental principles.

### 🗓️ Day 2: Flask and FastAPI Fundamentals
- **Teaching Approach:** `Syntax and coding`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Web frameworks for machine learning: Flask vs FastAPI
  - FastAPI advantages: asynchronous support, automatic interactive Swagger UI docs, type validation via Pydantic
  - Building a FastAPI application: routes, path parameters, query parameters, request bodies
  - Running local servers with Uvicorn (`uvicorn app:app --reload`)
- **Hands-on / Practical Implementation:**
  - Live coding session in VS Code / Jupyter Notebook demonstrating exact syntax, common error handling, and core code execution.

### 🗓️ Day 3: REST APIs and Model Integration
- **Teaching Approach:** `Practical examples`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Designing RESTful endpoints for ML prediction (`POST /predict`)
  - Validating input payload schemas using Pydantic `BaseModel`
  - Loading serialized ML models into memory at API startup (lifecycle lifespan)
  - Returning JSON prediction responses with status codes, error handling, and latency logging
- **Hands-on / Practical Implementation:**
  - Step-by-step practical coding of realistic scenarios, comparative examples, and interactive coding exercises for students.

### 🗓️ Day 4: Streamlit Application Development
- **Teaching Approach:** `Advanced concepts`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Introduction to Streamlit: rapid interactive web UI development in pure Python
  - Streamlit widgets: `st.title`, `st.sidebar`, `st.slider`, `st.selectbox`, `st.file_uploader`
  - Displaying interactive dataframes, metrics, and charts (`st.line_chart`, `st.pyplot`)
  - Building an interactive ML model prediction and EDA dashboard with Streamlit
- **Hands-on / Practical Implementation:**
  - Deep dive into inner mechanics, optimization techniques, edge cases, and best practice design patterns.

### 🗓️ Day 5: Docker and Cloud Deployment Introduction
- **Teaching Approach:** `Real-world applications`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - What is containerization and why 'it works on my machine' fails in production
  - Docker fundamentals: Dockerfile, Docker images, and Docker containers
  - Writing a production `Dockerfile` for Python/FastAPI/Streamlit ML applications
  - Cloud deployment options overview: Render, Hugging Face Spaces, Streamlit Community Cloud, AWS/GCP
- **Hands-on / Practical Implementation:**
  - End-to-end implementation of an industry-relevant mini-project or case study showing how these skills power AI/ML pipelines.

### 🗓️ Day 6: Model Serialization, Monitoring and MLOps Fundamentals
- **Teaching Approach:** `Exercises, assignments and weekly assessment`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Model serialization formats: Pickle, Joblib, ONNX (Open Neural Network Exchange)
  - Model drift, data drift, and the need for continuous production monitoring
  - MLOps lifecycle overview: tracking experiments with MLflow / Weights & Biases
  - Weekly assessment: Deploying a live Streamlit/FastAPI ML application with documentation
- **Hands-on / Practical Implementation:**
  - Guided lab review, live troubleshooting of assignment problems, timed coding challenge, and weekly assessment grading.

---

## 🎯 Weekly Assessment & Deliverables (Day 6)

At the conclusion of **Week 23**, each student is required to complete and submit the following:
1. **Coding Exercises:** Complete all daily coding tasks and store them in the respective practice files.
2. **Weekly Assessment Challenge:** Complete the designated practical assignment on **Model Deployment and MLOps**.
3. **Code Quality Review:** Ensure code adheres to PEP 8 standards, includes clean comments, and avoids anti-patterns.
4. **Knowledge Check:** Complete the short theoretical evaluation covering key terminology and design decisions.

---

## 💡 Pedagogical Notes for Instructors

> **Important Guidance:** This is part of an intensive 144-hour curriculum. Prioritize student progress, keyboard time, and hands-on coding capability over pure passive theory. Ensure every student types out the code and sees it execute successfully.
