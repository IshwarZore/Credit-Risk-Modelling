Here's your updated **README** with the **Streamlit application link** included:

---

# 📊 **Credit Risk Modelling**  

🚀 **Live Demo**: [Credit Risk Modelling Streamlit App](https://ishwar-zore-credit-risk-model.streamlit.app/)  

## Overview  

**Credit Risk Modelling** is a crucial area in finance that helps institutions assess the risk of lending to individuals or businesses. In this project, we build a machine learning model that predicts the likelihood of a borrower defaulting on a loan. By using historical loan data, we classify applicants as **low risk** or **high risk**.  

The project also includes an **interactive Streamlit web application** that allows users to input loan details and get real-time credit risk predictions.  

---

## 🏆 **Objective**  

To develop a machine learning model and an interactive web app that helps financial institutions assess **credit risk** based on applicant details.  

---

## 🔧 **Technologies Used**  

- **Programming Language**: Python  
- **Libraries**:  
  - `Pandas`, `NumPy` (for data manipulation)  
  - `Scikit-learn` (for building machine learning models)  
  - `Matplotlib`, `Seaborn` (for data visualization)  
  - `Streamlit` (for deploying the web application)  
- **Jupyter Notebooks** for experimentation and development  

---

## 🌱 **Features**  

- **Data Preprocessing**: Cleaning and preparing data for model building  
- **Feature Engineering**: Creating meaningful features for better model accuracy  
- **Model Building**: Implementing algorithms like Logistic Regression, Random Forest, and XGBoost  
- **Model Evaluation**: Using metrics like Accuracy, Precision, Recall, F1 Score, and AUC-ROC to assess performance  
- **Interactive Web App**: A Streamlit-powered app where users can input loan details and get real-time predictions  

---

## 🚀 **Installation & Setup**  

Follow these steps to get started with the project:  

### 1. Clone the repository  

```bash
git clone https://github.com/IshwarZore/Credit-Risk-Modelling.git
cd Credit-Risk-Modelling
```

### 2. Install required libraries  

It's recommended to create a virtual environment before installing dependencies:  

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

### 3. Run the Jupyter Notebook  

```bash
jupyter notebook
```

### 4. Run the Streamlit Web App Locally  

```bash
streamlit run app.py
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

The machine learning model achieves a high level of accuracy in predicting credit risk. Different algorithms like Logistic Regression, Random Forest, and XGBoost yield varying results, with trade-offs between accuracy and interpretability.  

---

## 🎯 **Streamlit Web App**  

### **🔗 Live Demo:** [Credit Risk Modelling Streamlit App](https://ishwar-zore-credit-risk-model.streamlit.app/)  

This project includes a **Streamlit web application** where users can input loan details and get **real-time credit risk predictions**. The app provides a **user-friendly interface** to interact with the trained machine learning model.  

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

🌟 **Check out the interactive Streamlit web app and explore Credit Risk Modelling!** 🌟  

---

Now, your README includes the **Streamlit app link**, making it more engaging and informative! Let me know if you need any more tweaks. 🚀
