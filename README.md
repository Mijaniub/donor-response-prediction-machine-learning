┌──────────────────────────────────────────────────────────────┐
│                                                              │
│        Predicting Donor Response using Machine Learning      │
│                                                              │
│      Binary Classification • Python • Scikit-Learn          │
│        Data Science • NOVA IMS Portfolio Project             │
│                                                              │
└──────────────────────────────────────────────────────────────┘



# 🎯 Predicting Donor Response using Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-0099CC?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

> An end-to-end Machine Learning project focused on predicting donor response for fundraising campaigns using binary classification techniques.

> **Note:** This project was completed as part of a group assignment for the **Data Science & Machine Learning** course at **NOVA Information Management School (NOVA IMS)**. This repository is shared as part of my professional portfolio to demonstrate the machine learning techniques, analytical workflow, and business insights explored during the project.

---

# 📌 Executive Summary

## 📑 Table of Contents

- [Executive Summary](#-executive-summary)
- [Business Problem](#-business-problem)
- [Dataset](#-dataset)
- [Project Workflow](#️-project-workflow)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Data Preprocessing](#-data-preprocessing)
- [Machine Learning Models](#-machine-learning-models)
- [Model Evaluation](#-model-evaluation)
- [Final Model](#-final-model)
- [Business Insights](#-business-insights)
- [Repository Structure](#-repository-structure)
- [Technologies Used](#-technologies-used)
- [Future Improvements](#-future-improvements)
- [Project Team](#-project-team)
- [Portfolio Author](#-portfolio-author)

Nonprofit organizations often contact thousands of potential donors during fundraising campaigns. However, sending outreach to every individual is inefficient, costly, and may reduce donor engagement over time.

This project aims to develop a predictive machine learning model capable of identifying individuals who are most likely to donate if contacted. Using historical donor data, the project follows a complete data science workflow, including data preprocessing, exploratory data analysis, feature engineering, model development, evaluation, optimization, and prediction generation.

The final solution provides a data-driven approach that can help organizations improve campaign effectiveness while optimizing marketing resources and donor engagement.

---

# 🎯 Business Problem

The Civic Support Alliance (CSA) wanted to modernize its fundraising strategy by replacing mass outreach campaigns with a targeted approach.

Instead of contacting every individual in their database, the objective was to identify people with the highest probability of making a donation.

The business question addressed in this project is:

> **Can we accurately predict whether a person will donate if contacted?**

Successfully solving this problem enables organizations to:

- Increase fundraising efficiency
- Reduce unnecessary campaign costs
- Improve donor engagement
- Support data-driven decision making

---

## 🚀 Project Highlights

- ✅ End-to-end Machine Learning pipeline
- ✅ Binary Classification
- ✅ Data Cleaning & Feature Engineering
- ✅ Exploratory Data Analysis (EDA)
- ✅ Multiple Machine Learning Models
- ✅ Model Evaluation & Optimization
- ✅ Kaggle Competition Submission
- ✅ Business-focused Insights

# 📊 Dataset

The project uses historical fundraising campaign data containing donor demographic information, previous interactions, and donation behavior.

The datasets include:

- Training dataset
- Training target labels
- Test dataset
- Kaggle submission template

The target variable is:

**TARGET_B**

- **1** → Donated
- **0** → Did not donate

---

# ⚙️ Project Workflow

```
Raw Data
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Data Preprocessing
      │
      ▼
Machine Learning Models
      │
      ▼
Model Evaluation
      │
      ▼
Hyperparameter Optimization
      │
      ▼
Final Prediction
```

---

# 📈 Exploratory Data Analysis

The exploratory analysis focused on understanding the characteristics of the dataset before model development.

Key activities included:

- Dataset exploration
- Missing value analysis
- Feature distributions
- Correlation analysis
- Outlier detection
- Target variable analysis

The insights obtained during EDA guided the preprocessing and feature engineering decisions used throughout the project.

---

# 🧹 Data Preprocessing

To prepare the dataset for machine learning, several preprocessing techniques were applied, including:

- Handling missing values
- Removing duplicate records
- Feature transformation
- Encoding categorical variables
- Feature scaling
- Data quality validation
- Preparation of training and testing datasets

These steps ensured that the models received clean, consistent, and reliable input data.

---

# 🤖 Machine Learning Models

Several binary classification algorithms were explored and compared to identify the most suitable predictive model.

The overall modeling process included:

- Model training
- Performance comparison
- Cross-validation / validation strategy
- Hyperparameter optimization
- Selection of the best-performing model

The final model was selected based on its overall predictive performance and generalization capability.

--- 

# 📉 Model Evaluation

Model performance was assessed using appropriate classification metrics, including:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC (where applicable)
- Confusion Matrix

The evaluation process ensured that the selected model balanced predictive accuracy with practical business value.

---

# 📷 Project Visualizations

### Correlation Analysis

![Correlation](images/correlation_heatmap.png)

---

### Missing Values

![Missing Values](images/missing_values.png)

---

### Model Comparison

![Model Comparison](images/model_comparison.png)

---

### ROC Curve

![ROC Curve](images/roc_curve.png)

---

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)


# 🏆 Final Model

After comparing multiple machine learning models and optimization strategies, the best-performing model was selected to generate predictions for unseen donor data.

The final model was used to produce the submission file for the Kaggle competition while maintaining a balance between predictive performance and model reliability.

---

# 💡 Business Insights

This project demonstrates how machine learning can support smarter fundraising decisions.

Potential business benefits include:

- More targeted fundraising campaigns
- Better donor engagement
- Improved resource allocation
- Reduced outreach costs
- Higher campaign efficiency
- Data-driven decision making

Rather than contacting every potential donor, organizations can focus their efforts on individuals with the highest probability of making a donation.

---

# 📁 Repository Structure

```
donor-response-prediction-machine-learning/

│── data/
│── notebooks/
│── images/
│── models/
│── src/
│── README.md
│── requirements.txt
│── LICENSE
│── .gitignore
```

---

# 🛠 Technologies Used

| Category | Technologies |
|-----------|--------------|
| **Programming Language** | Python |
| **Data Analysis** | Pandas, NumPy |
| **Data Visualization** | Matplotlib, Seaborn |
| **Machine Learning** | Scikit-learn |
| **Development Environment** | Jupyter Notebook |
| **Version Control** | Git & GitHub |
| **Techniques Applied** | Exploratory Data Analysis (EDA), Data Preprocessing, Feature Engineering, Binary Classification, Model Evaluation, Cross Validation, Hyperparameter Optimization |
---

# 🚀 Future Improvements

Potential improvements include:

- Advanced feature engineering
- Automated hyperparameter optimization
- Probability calibration
- Model interpretability using SHAP
- Deployment as a web application
- Continuous model monitoring
- Real-time prediction pipeline

---

---

# 👥 Project Team

This project was completed as a **group assignment** for the **Data Science & Machine Learning** course at **NOVA Information Management School (NOVA IMS)**.

### Team Members

- Francisco Pinto
- João Poças
- Simão Prazeres
- MD Mijanul Haque

---

# 👨‍💻 Portfolio Author

This repository is maintained by **MD Mijanul Haque** as part of his professional Data Science portfolio.

**Postgraduate in Enterprise Data Science & Analytics**  
**NOVA Information Management School (NOVA IMS)**

### 🔗 Connect with Me

- **LinkedIn:** https://www.linkedin.com/in/md-mijanul-haque-165188212/
- **GitHub:** https://github.com/Mijaniub

---

# 📌 Portfolio Note

This repository showcases a machine learning project completed collaboratively as part of the **Data Science & Machine Learning** course at **NOVA IMS**.

The project is included in my professional portfolio to demonstrate practical experience in:

- End-to-end Machine Learning workflows
- Data preprocessing and feature engineering
- Binary classification and model evaluation
- Business-oriented data analysis
- Collaborative software development

The implementation and results presented in this repository reflect the collective contributions of the project team.

---

## ⭐ Support the Project

If you found this project useful or interesting, please consider giving it a ⭐ on GitHub. Feedback, suggestions, and contributions are always welcome!
