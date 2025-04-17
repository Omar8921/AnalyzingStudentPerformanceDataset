# 📊 Student Performance Analysis

This project performs an exploratory data analysis (EDA) on student exam performance using Python. The goal is to uncover patterns related to gender, parental education, lunch types, and test preparation, and how these factors influence student scores in math, reading, and writing.

---

## 📁 Dataset

- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Attributes**: Gender, race/ethnicity, parental level of education, lunch type, test preparation course, and scores in math, reading, and writing.

---

## 🎯 Objectives

- Understand demographic and socioeconomic factors affecting performance.
- Visualize performance distributions by group (e.g., gender, ethnicity).
- Identify key correlations among scores.
- Provide data-driven suggestions for interventions.

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ✅ Results

- **Balanced Gender Distribution**: The dataset is not gender-biased, ensuring fair comparisons across male and female students.
- **Financial Hardship Is Common**: A large portion of students rely on free/reduced lunch, highlighting the impact of socioeconomic status on academic life.
- **Test Prep Neglected**: Nearly two-thirds of students skipped the test preparation course, suggesting disinterest or financial limitations.
- **Subject Performance Is Correlated**: Strong positive correlation among math, reading, and writing scores—excelling in one typically means excelling in others.
- **Reading Outperforms Math/Writing**: Reading scores are generally higher, possibly indicating better teaching methods in reading.
- **Group C Is a Key Focus**: It’s the largest group and shows economic diversity—ideal for targeting educational equity programs.
- **Parental Education Is Limited**: Most parents don’t have postgraduate degrees, which may affect academic support at home.
- **Female Students Excel**: Girls perform better overall, likely influenced by higher parental education levels.
- **Early Risk Prediction Possible**: Strong inter-subject score correlation allows schools to identify at-risk students early.
- **Outliers Are Genuine**: Outliers in performance are consistent across all subjects, confirming they are not errors but real indicators of academic struggle.

---

## 🧠 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-performance-analysis.git
   cd student-performance-analysis
