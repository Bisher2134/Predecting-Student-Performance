# 🎓 Predicting Student Exam Success — A Beginner’s Guide to Data Science

A beginner-friendly mini-course for aspiring data scientists — built around one real-world question:

> **Can we predict whether a student will pass or fail their final exam using simple features like study time, absences, and previous grades?**

This project walks learners through the entire data science workflow using Python, the UCI Student Performance dataset, and an interactive Gradio app — perfect for interns, educators, or junior data scientists building a portfolio.

---

## 🌟 Learning Outcomes

By the end of this course, students will be able to:

- ✅ Load and analyze tabular student data  
- 🧠 Train a classification model using scikit-learn  
- 📊 Evaluate model accuracy, fairness, and feature importance  
- 🎮 Build a real-time prediction app with Gradio  
- 🔍 Apply EDA, mutual information, and confusion matrices

---

## 🧱 Folder & File Overview

| File / Folder        | Description                                      |
|----------------------|--------------------------------------------------|
| `lesson1.ipynb`      | Load, clean, and explore the dataset             |
| `lesson2.ipynb`      | Build and evaluate a logistic regression model   |
| `lesson3.ipynb`      | Analyze confusion matrix and feature influence   |
| `lesson4_app.py`     | Build an interactive prediction app (Gradio)     |
| `student_exam.csv`   | Cleaned dataset used throughout the course       |
| `README.md`          | Course documentation (← you're reading it!)      |

---

## ⚙️ Setup Instructions

### ✳️ Requirements:
- Python 3.8+
- Jupyter Notebook
- `pandas`, `numpy`, `seaborn`, `matplotlib`
- `scikit-learn`, `gradio`

### ✅ Installation:
```bash
# Clone the repo
git clone https://github.com/<your-username>/student-success-predictor
cd student-success-predictor

# Install dependencies
pip install pandas numpy seaborn matplotlib scikit-learn gradio

# Start Jupyter Notebook
jupyter notebook

# Step-by-step progression:
- Run `lesson1.ipynb`  → Explore the data
- Then `lesson2.ipynb` → Train a classification model
- Then `lesson3.ipynb` → Analyze model results
- Then run `lesson4_app.py` → Launch the Gradio prediction app
