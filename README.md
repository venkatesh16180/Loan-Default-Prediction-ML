# Loan Default Prediction — Binary Classification
**Course: Introduction to Machine Learning | University of Arizona**

---

## 📌 Overview
A binary classification project predicting customer loan default risk 
using the **German Bank Credit Dataset**. The project compares three 
Logistic Regression models trained on datasets processed with different 
missing value treatment strategies, using both Scikit-learn and 
Statsmodels for modeling and statistical validation.

---

## 📁 Repository Structure
Loan-Default-Prediction-ML/

│

├── Assignment_6.ipynb       # Main modeling notebook

├── Project_Report.docx      # Full written project report

└── README.md

---

## 📊 Dataset
**German Bank Credit Dataset**
- 1,000 customer records, 16 features
- Target variable: binary loan default (yes/no)
- Features include: credit history, savings balance, employment 
  duration, loan amount, age, housing status

---

## 🧠 Approach
Compared **3 Logistic Regression models** trained on differently 
processed versions of the dataset:

| Model | Missing Value Strategy | Accuracy |
|---|---|---|
| Model 1 | Row dropping | Baseline |
| Model 2 | SimpleImputer (mode) | Improved |
| Model 3 | KNNImputer | **70%** (best) |

---

## 🔑 Key Tasks
- Performed EDA and identified missing values across 2 key features
- Applied 3 missing value strategies and compared their downstream 
  impact on model performance
- Built Logistic Regression models using both **Scikit-learn** and 
  **Statsmodels Logit**
- Conducted **statistical significance analysis** using Logit summary 
  tables — p-values and coefficients for each feature
- Evaluated models using accuracy score and classification reports

## 💡 Key Finding
Customers with **perfect credit history** showed a statistically 
higher likelihood of default — a counterintuitive result validated 
through positive coefficient values and low p-values in the Logit 
summary. This highlights the importance of statistical interpretation 
beyond surface-level accuracy metrics.

---

## 🛠️ Tools & Technologies
| Category | Tools |
|---|---|
| Language | Python |
| ML Modeling | Scikit-learn (LogisticRegression, KNNImputer, SimpleImputer) |
| Statistical Analysis | Statsmodels (Logit, summary tables) |
| Data Analysis | Pandas, NumPy |
| Evaluation | Accuracy Score, Classification Report, P-values, Coefficients |
| Environment | Jupyter Notebook |

---

## 🚀 How to Run
1. Clone the repository:
```bash
   git clone https://github.com/venkatesh16180/Loan-Default-Prediction-ML.git
```
2. Install dependencies:
```bash
   pip install pandas numpy scikit-learn statsmodels jupyter
```
3. Open the notebook:
```bash
   jupyter notebook Assignment_6.ipynb
```

---

## 👤 Author
**Venkateshwara Chowdary Tallapaneni**
MS Information Sciences (Machine Learning) | University of Arizona
[LinkedIn](https://www.linkedin.com/in/venkateshwara-chowdary-tallapaneni) | 
[GitHub](https://github.com/venkatesh16180)
