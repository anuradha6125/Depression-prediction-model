# Analysis and Prediction Model for Student Depression

This project is a step towards understanding and predicting depression among students using machine learning techniques. It aims to analyze various factors that contribute to mental health challenges and provide insights for early intervention.

---

## 📋 Dataset Overview

The dataset contains various features related to student demographics, academic and work pressures, and lifestyle habits. Below is a brief overview:

| **Feature**                     | **Description**                                  |
|----------------------------------|--------------------------------------------------|
| `ID`                             | Unique identifier for each student              |
| `Gender`                         | Gender of the student                           |
| `Age`                            | Age of the student                              |
| `City`                           | Location of the student                         |
| `Profession`                     | Profession (Student/Working Professional)       |
| `Academic Pressure`              | Academic stress level (numerical scale)         |
| `Work Pressure`                  | Work stress level (numerical scale)             |
| `CGPA`                           | Academic performance (GPA)                      |
| `Study Satisfaction`             | Satisfaction with study habits (scale)          |
| `Job Satisfaction`               | Satisfaction with job (scale)                   |
| `Sleep Duration`                 | Average sleep duration in hours                 |
| `Dietary Habits`                 | Diet quality (scale)                            |
| `Degree`                         | Degree being pursued                            |
| `Have you ever had suicidal thoughts?` | Binary response (Yes/No)                     |
| `Work/Study Hours`               | Average hours of work or study                  |
| `Financial Stress`               | Level of financial stress                       |
| `Family History of Mental Illness` | Binary response (Yes/No)                      |
| `Depression`                     | Target variable (Depressed/Not Depressed)       |

---

## 🚀 Project Highlights

- **Machine Learning Algorithm Used**: Multinomial Naive Bayes (`alpha=1`)
- **Accuracy Achieved**: 82%
- **Key Features Influencing Depression**:
  - Academic Pressure & Age
  - Study Hours
  - Financial Stress
  - Family History of Mental Illness
  - Sleep Duration and Dietary Habits

---

## 📊 Tools and Technologies

- **Programming Language**: Python
- **Libraries Used**:
  - `pandas` for data manipulation
  - `numpy` for numerical computations
  - `scikit-learn` for machine learning models
  - `matplotlib` and `seaborn` for data visualization

---

## 💡 Key Learnings and Insights

1. Data preprocessing and feature selection play a crucial role in model performance.
2. Mental health prediction models can help identify at-risk individuals early.
3. There is scope to improve the model using advanced algorithms like Random Forest or Neural Networks.

---

## 🛠️ How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/student-depression-prediction.git
