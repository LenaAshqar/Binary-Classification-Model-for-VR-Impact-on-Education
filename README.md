# 📊 Virtual Reality in Education — Impact Prediction

> A machine learning project that analyzes and predicts the effectiveness of Virtual Reality (VR) in enhancing students’ learning outcomes.

---

## 🚀 Overview

Virtual Reality (VR) is transforming education, but its effectiveness varies across students and contexts.

This project explores:
- 📈 How VR usage impacts learning outcomes  
- 🧠 What factors influence student engagement and perception  
- 🤖 How to predict whether VR improves educational performance  

We build multiple classification models to predict whether VR positively impacts a student’s learning.

---

## 🎯 Problem Statement

Can we predict whether VR improves a student’s learning outcomes based on:

- Demographics  
- Academic performance  
- Engagement level  
- VR usage (hours, access, etc.)

---

## 🧪 Objectives

- Analyze relationships between VR usage and learning outcomes  
- Identify key factors affecting VR effectiveness  
- Build and evaluate classification models  
- Compare multiple ML approaches  

---

## 📂 Dataset

- **Observations:** 5000 students  
- **Features:** 20 variables  
- **Types:**
  - Categorical: Gender, Grade Level, Subject, VR Usage  
  - Numerical: Hours of VR, Engagement Level, Creativity Impact  

---

## ⚙️ Project Pipeline

### 1. 🔍 Discovery
- Define problem, objectives, and hypothesis  
- Understand dataset structure  

### 2. 🧹 Data Preparation
- Introduced:
  - Missing values  
  - Outliers (via IQR)  
  - Inconsistencies  
- Cleaned:
  - Imputed missing data  
  - Fixed data types  
  - Removed outliers  
- Encoded categorical variables  

### 3. 📊 Exploratory Data Analysis (EDA)
- Statistical summaries  
- Univariate, bivariate, and multivariate visualizations  
- Relationship analysis between variables  

### 4. 🤖 Model Building

Implemented multiple classification models:

- 🌿 Decision Tree  
- 🌲 Random Forest  
- 📊 Gaussian Naive Bayes  
- 📊 Categorical Naive Bayes  

---

## 🧠 Hypothesis

Students with:
- Higher engagement  
- More VR usage hours  
- Better academic performance  

➡️ Are more likely to perceive VR as effective in learning.

---

## 📈 Results

- Compared model performance across different algorithms  
- Identified key predictive features  
- Evaluated accuracy and generalization  

*(Add metrics like accuracy, precision, recall here if available)*

---

## 👥 Team & Contributions

| Member | Responsibilities |
|--------|-----------------|
| **Nermin Alnosair** | Data preparation, Gaussian NB model |
| **Afrah Alsubhi** | EDA (univariate), Decision Tree |
| **Maryam Alsalman** | Advanced EDA, Categorical NB |
| **Lena Ashqar** | Reporting, Random Forest, relationship analysis |

---

## 🛠️ Tech Stack

- Python 🐍  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## ▶️ How to Run

```bash
# Clone the repository
git clone <repo-url>

# Navigate into the project
cd <project-folder>

# Open the notebook
jupyter notebook "Project Report.ipynb"
```

Alternatively:

Download the notebook and run it in Google Colab.

## 📌 Key Takeaways
- VR effectiveness depends on multiple interacting factors
- Engagement level is a strong predictor
- Ensemble models (like Random Forest) tend to perform better
