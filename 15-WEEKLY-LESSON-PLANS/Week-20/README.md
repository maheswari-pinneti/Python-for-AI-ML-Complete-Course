# Week 20 – Deep Learning Frameworks

> **Phase:** Phase 7 – Deep Learning  
> **Duration:** 6 Days (1 Hour / Day = 6 Hours Total)  
> **Course Framework:** 144 Hours – Python for AI/ML Complete Course  

---

## 📌 Weekly Overview

Welcome to **Week 20** of the **Python for AI/ML** curriculum. In this module, students focus on **Deep Learning Frameworks** within **Phase 7 – Deep Learning**. The curriculum is structured with a progressive 6-day daily pedagogy: starting with conceptual grounding, moving to syntax and coding, exploring practical examples, deepening through advanced concepts and real-world applications, and culminating in hands-on exercises and weekly assessment on Day 6.

---

## 📅 Daily Teaching Schedule

| Day | Topic | Teaching Approach | Core Focus / Deliverable |
| :--- | :--- | :--- | :--- |
| **Day 1** | Introduction to TensorFlow | *Concepts and theory* | Overview of industry-standard deep learning frameworks: TensorFlow vs PyTorch |
| **Day 2** | Keras and Neural Network Implementation | *Syntax and coding* | The Keras high-level API (`tf.keras`): Sequential model vs Functional API |
| **Day 3** | Introduction to PyTorch and Tensors | *Practical examples* | PyTorch core philosophy: dynamic computation graphs (define-by-run) |
| **Day 4** | Convolutional Neural Networks (CNN) | *Advanced concepts* | Why dense layers fail for images: parameter explosion and spatial invariance |
| **Day 5** | Recurrent Neural Networks (RNN) and Transfer Learning | *Real-world applications* | Sequential modeling: standard RNNs and the exploding/vanishing gradient problem |
| **Day 6** | Image Classification Project | *Exercises, assignments and weekly assessment* | Building an image classification model using CNN / Transfer Learning (e.g. CIFAR-10 or custom dataset) |

---

## 📖 Detailed Daily Lesson Plans

### 🗓️ Day 1: Introduction to TensorFlow
- **Teaching Approach:** `Concepts and theory`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Overview of industry-standard deep learning frameworks: TensorFlow vs PyTorch
  - TensorFlow 2.x ecosystem and architecture
  - Tensors: creation, shape, rank, datatype, and mathematical operations
  - Automatic differentiation with `tf.GradientTape`
- **Hands-on / Practical Implementation:**
  - Conceptual walkthrough with architectural whiteboard / markdown notes, live code demonstration of primary concepts, and Q&A on fundamental principles.

### 🗓️ Day 2: Keras and Neural Network Implementation
- **Teaching Approach:** `Syntax and coding`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - The Keras high-level API (`tf.keras`): Sequential model vs Functional API
  - Building an MLP: `Dense`, `Dropout`, `BatchNormalization` layers
  - Compiling models: specifying optimizer (`'adam'`), loss function, and metrics
  - Training with `.fit()`, validation splits, and plotting training history curves
- **Hands-on / Practical Implementation:**
  - Live coding session in VS Code / Jupyter Notebook demonstrating exact syntax, common error handling, and core code execution.

### 🗓️ Day 3: Introduction to PyTorch and Tensors
- **Teaching Approach:** `Practical examples`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - PyTorch core philosophy: dynamic computation graphs (define-by-run)
  - PyTorch Tensors: operations, GPU acceleration (`tensor.to('cuda')`)
  - `torch.autograd` and gradient tracking (`requires_grad=True`)
  - Building a neural network module subclassing `nn.Module` and implementing `forward()`
- **Hands-on / Practical Implementation:**
  - Step-by-step practical coding of realistic scenarios, comparative examples, and interactive coding exercises for students.

### 🗓️ Day 4: Convolutional Neural Networks (CNN)
- **Teaching Approach:** `Advanced concepts`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Why dense layers fail for images: parameter explosion and spatial invariance
  - Convolution operation: kernels/filters, stride, padding ('valid' vs 'same')
  - Feature maps and Pooling layers (Max Pooling, Average Pooling)
  - Classic CNN architectures overview: LeNet, AlexNet, VGG, ResNet (residual connections)
- **Hands-on / Practical Implementation:**
  - Deep dive into inner mechanics, optimization techniques, edge cases, and best practice design patterns.

### 🗓️ Day 5: Recurrent Neural Networks (RNN) and Transfer Learning
- **Teaching Approach:** `Real-world applications`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Sequential modeling: standard RNNs and the exploding/vanishing gradient problem
  - Gated architectures: Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU)
  - Transfer Learning concept: feature extraction vs fine-tuning pre-trained models
  - Using pre-trained weights (e.g. MobileNetV2, ResNet50) from `tf.keras.applications`
- **Hands-on / Practical Implementation:**
  - End-to-end implementation of an industry-relevant mini-project or case study showing how these skills power AI/ML pipelines.

### 🗓️ Day 6: Image Classification Project
- **Teaching Approach:** `Exercises, assignments and weekly assessment`
- **Class Duration:** 1 Hour (60 minutes)
- **Key Topics Covered:**
  - Building an image classification model using CNN / Transfer Learning (e.g. CIFAR-10 or custom dataset)
  - Data augmentation (`RandomFlip`, `RandomRotation`, `RandomZoom`) to prevent overfitting
  - Evaluating test accuracy, loss curves, and classification report
  - Weekly assessment: Image classification notebook submission and evaluation rubric
- **Hands-on / Practical Implementation:**
  - Guided lab review, live troubleshooting of assignment problems, timed coding challenge, and weekly assessment grading.

---

## 🎯 Weekly Assessment & Deliverables (Day 6)

At the conclusion of **Week 20**, each student is required to complete and submit the following:
1. **Coding Exercises:** Complete all daily coding tasks and store them in the respective practice files.
2. **Weekly Assessment Challenge:** Complete the designated practical assignment on **Deep Learning Frameworks**.
3. **Code Quality Review:** Ensure code adheres to PEP 8 standards, includes clean comments, and avoids anti-patterns.
4. **Knowledge Check:** Complete the short theoretical evaluation covering key terminology and design decisions.

---

## 💡 Pedagogical Notes for Instructors

> **Important Guidance:** This is part of an intensive 144-hour curriculum. Prioritize student progress, keyboard time, and hands-on coding capability over pure passive theory. Ensure every student types out the code and sees it execute successfully.
