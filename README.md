# 📊 **Credit Risk Modelling**

## Overview

**Credit Risk Modelling** is a crucial area in finance that helps institutions assess the risk of lending to individuals or businesses. In this project, we build a machine learning model that predicts the likelihood of a borrower defaulting on a loan. By using historical loan data, we classify applicants as low or high risk.

The objective is to create a model that assists financial institutions in making informed decisions about loan approvals.

---

## 🏆 **Objective**

To predict credit risk using machine learning by analyzing a dataset of loan applicants and their characteristics. The model classifies each applicant as **low risk** or **high risk**.

---

## 🔧 **Technologies Used**

- **Programming Language**: Python
- **Libraries**: 
  - `Pandas`, `NumPy` (for data manipulation)
  - `Scikit-learn` (for building machine learning models)
  - `Matplotlib`, `Seaborn` (for data visualization)
- **Jupyter Notebooks** for experimentation and development

---

## 🌱 **Features**

- **Data Preprocessing**: Cleaning and preparing data for model building.
- **Feature Engineering**: Deriving new features to improve model accuracy.
- **Model Building**: Implementing algorithms like Logistic Regression, Random Forest, and XGBoost.
- **Model Evaluation**: Using metrics like Accuracy, Precision, Recall, F1 Score, and AUC-ROC to evaluate performance.
- **Visualization**: Visualizing performance using ROC curves, confusion matrices, and more.

---

## 🚀 **Installation & Setup**

Follow these steps to get started with the project:

### 1. Clone the repository

```bash
git clone https://github.com/IshwarZore/Credit-Risk-Modelling.git
cd Credit-Risk-Modelling
```

### 2. Install required libraries

It’s recommended to create a virtual environment first:

```bash
# Install virtualenv if not installed
pip install virtualenv

# Create a virtual environment
virtualenv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On MacOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

### 3. Launch the Jupyter Notebook

```bash
jupyter notebook
```

---

## 📝 **Dataset**

The dataset contains information about loan applicants, including:

- **Age**: Applicant's age
- **Income**: Monthly income
- **Credit History**: Credit status of the applicant
- **Loan Amount**: Loan being applied for
- **Debt-to-Income Ratio**: Ratio of debt to income
- **Marital Status**: Applicant's marital status

---

## 📊 **Model Evaluation**

The model is evaluated using the following metrics:

- **Accuracy**: Correctly predicted instances
- **Precision**: Proportion of positive predictions that are correct
- **Recall**: Proportion of actual positives that were predicted
- **F1 Score**: The harmonic mean of Precision and Recall
- **AUC-ROC Curve**: Measures the ability to distinguish between classes

---

## 📈 **Results**

The model achieves a good level of performance in predicting credit risk. Depending on the algorithms used (e.g., Logistic Regression, Random Forest, XGBoost), the results may vary in terms of accuracy and precision.

---

## 🤝 **Contributing**

We welcome contributions! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -m "Your message"`)
5. Push to your fork (`git push origin feature-branch`)
6. Open a pull request

---

## 🛡️ **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

🌟 **Enjoy working with the Credit Risk Modelling project!** 🌟
