# 💳 CreditPathAI – Loan Default Risk Prediction

**Infosys Springboard Data and AI Virtual Internship | Oct – Dec 2025**

## 📌 Overview
CreditPathAI is a machine learning-based project that predicts loan default risk using borrower and loan-related information. It analyzes historical data to classify borrowers as defaulters or non-defaulters.

## 🎯 Objectives
- Analyze loan data and identify default patterns.
- Build machine learning classification models.
- Evaluate model performance.
- Develop an interactive loan risk prediction application.

## 👩‍💻 My Contribution
- Performed data cleaning, preprocessing and exploratory data analysis (EDA).
- Applied feature encoding, scaling and SMOTE for handling class imbalance.
- Implemented and evaluated multiple machine learning algorithms.
- Developed a Streamlit application for loan default risk prediction.

## 📊 Dataset
- **Records:** 148,671+
- **Target Variable:** `Status`
  - `0` – Non-Defaulter
  - `1` – Defaulter

**Key Features:** Loan Amount, Income, Credit Score, LTV, DTIR1, Gender, Loan Purpose, Age, Region and Employment Status.

## ⚙️ Workflow
1. Data Loading and Cleaning
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering and Scaling
5. Handling Class Imbalance using SMOTE
6. Model Training and Evaluation
7. Streamlit Application Development

## 🤖 Machine Learning Models
- Logistic Regression
- Naive Bayes
- Decision Tree
- Random Forest
- XGBoost
- K-Nearest Neighbors (KNN)

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Imbalanced-learn
- **Tools:** Google Colab, Jupyter Notebook, Streamlit, Git & GitHub

## 📈 Results
**Logistic Regression Accuracy: 87.44%**

Confusion Matrix:

| Actual / Predicted | Non-Defaulter | Defaulter |
|---|---:|---:|
| Non-Defaulter | 22,117 | 289 |
| Defaulter | 3,445 | 3,883 |

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone <your-repository-url>
cd CreditPathAI
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Run the application**
```bash
streamlit run app.py
```

## 📁 Project Files
- `Main.ipynb` – Data analysis and model development
- `app.py` – Streamlit prediction application
- `requirements.txt` – Project dependencies
- `models/` – Trained model files
- `results/` – Model evaluation results

## 🤝 Team & Acknowledgement
- **Program:** Infosys Springboard Data and AI Virtual Internship
- **Project Type:** Team Project
---

⭐ *Developed as part of the Infosys Springboard Virtual Internship (Oct – Dec 2025).* 
