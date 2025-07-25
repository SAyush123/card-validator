# 🧠 Employee Salary Prediction using Machine Learning

This project aims to predict whether a person's income exceeds \$50K per year based on various demographic and employment attributes. It uses the **UCI Adult Census Income Dataset** and applies a **Random Forest Classifier** to make accurate predictions.

---

## 📁 Dataset

- Source: [UCI Machine Learning Repository - Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
- File Used: `adult.csv`
- Attributes: Age, Workclass, Education, Occupation, Hours-per-week, etc.
- Target Variable: `income` (<=50K or >50K)

---

## 📊 Project Workflow

1. **Data Loading & Cleaning**
   - Removed or replaced unknown/missing values.
   - Label encoded categorical features.

2. **Feature Engineering**
   - Selected important features.
   - Encoded using `LabelEncoder`.

3. **Modeling**
   - Trained using `RandomForestClassifier`.
   - 80/20 Train-Test split.

4. **Evaluation**
   - Accuracy: **86.35%**
   - F1 Score (>50K): **68.78%**
   - Visualized feature importance.

---

## 📈 Results

| Metric         | Value     |
|----------------|-----------|
| Accuracy       | 86.35%    |
| Precision >50K | 74.15%    |
| Recall >50K    | 64.15%    |
| F1 Score >50K  | 68.78%    |

---

## 🔧 Technologies Used

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

---