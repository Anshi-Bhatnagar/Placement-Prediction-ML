# 🎓 Placement Prediction using Machine Learning

## 📌 Overview

This project predicts whether a student will be placed based on academic performance and employability-related factors using Machine Learning techniques.

The project follows a complete machine learning workflow including data preprocessing, exploratory data analysis (EDA), feature selection, model training, evaluation, feature importance analysis, and feature engineering experiments.

---
## ✨ Highlights

- Built and evaluated 3 Machine Learning classification models.
- Achieved 86.05% accuracy using Decision Tree Classifier.
- Performed Feature Importance Analysis and Cross Validation.
- Conducted Feature Engineering experiments using categorical variables.
- Created visualizations for model evaluation and comparison.

---

## 🎯 Objective

To build a classification model that can predict placement outcomes based on student academic records and employability test scores.

---

## 📊 Dataset

**Source:** Campus Placement Dataset

**Total Records:** ~215 students

### Features Used

- SSC Percentage (`ssc_p`)
- HSC Percentage (`hsc_p`)
- Degree Percentage (`degree_p`)
- Employability Test Score (`etest_p`)
- MBA Percentage (`mba_p`)

### Target Variable

- Placed → 1
- Not Placed → 0

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Google Colab

---

## 🔍 Exploratory Data Analysis

Performed EDA to understand relationships between academic performance and placement outcomes.

### Visualizations

- Correlation Heatmap
- SSC vs Placement Scatter Plot
- SSC Distribution Box Plot
- Confusion Matrix
- Feature Importance Analysis
- Model Comparison Chart

---

## 🤖 Machine Learning Models

### Logistic Regression
Accuracy: **79.07%**

### Random Forest
Accuracy: **81.40%**

### Decision Tree
Accuracy: **86.05%** ✅

Decision Tree achieved the highest accuracy and was selected as the final model.

---

## 📈 Model Comparison

| Model | Accuracy |
|---------|---------:|
| Logistic Regression | 79.07% |
| Random Forest | 81.40% |
| Decision Tree | 86.05% |

---

## 🔥 Key Findings

- SSC Percentage was the most influential feature.
- MBA Percentage was the second most important predictor.
- Academic performance showed strong correlation with placement outcomes.
- Employability Test Score had comparatively lower impact.
- Decision Tree outperformed Logistic Regression and Random Forest on this dataset.

---

## 🧪 Feature Engineering Experiment

Additional categorical features were incorporated using one-hot encoding:

- Gender
- Work Experience
- Specialization
- Degree Type
- HSC Stream

Results showed that these features did not improve predictive performance on the current dataset, indicating that academic indicators remained the strongest predictors.

---

## 📂 Project Workflow

1. Data Cleaning
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Selection
5. Model Training
6. Model Evaluation
7. Feature Importance Analysis
8. Feature Engineering Experiment
9. Cross Validation
10. Final Model Selection

---
## 📊 Project Visualizations

## Model Comparison Graph

<img width="700" height="470" alt="image" src="https://github.com/user-attachments/assets/f5ea1c16-e8ed-4df5-9e17-855e94d26be3" />

---

## Feature Importance Graph

<img width="721" height="451" alt="image" src="https://github.com/user-attachments/assets/fa195f64-5817-4972-84ff-975b4dd69552" />

---

## Confusion Matrix

<img width="501" height="393" alt="image" src="https://github.com/user-attachments/assets/dd161776-327c-43be-b25f-65aea9b8df7b" />

---
## Cross Validation

5-Fold Cross Validation was performed to evaluate model stability.

Cross Validation Scores:
- 83.72%
- 81.40%
- 81.40%
- 76.74%
- 69.77%

Mean Accuracy: 78.60%

The results indicate that the model generalizes reasonably well across different data splits, although performance varies due to the relatively small dataset size.

---
## 🚀 Future Improvements

- Hyperparameter Tuning
- XGBoost Implementation
- Streamlit Web Application
- Larger Dataset Integration
- Additional Features (Internships, Certifications, Technical Skills)

---

## 👩‍💻 Author

**Anshika Bhatnagar**

B.Tech Information Technology  
Harcourt Butler Technical University (HBTU), Kanpur

GitHub: Anshi-Bhatnagar
