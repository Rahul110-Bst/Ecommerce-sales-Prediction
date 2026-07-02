# 📊 End-to-End E-commerce Customer Churn Prediction

An end-to-end Machine Learning project that predicts whether an e-commerce customer is likely to churn based on demographic and service-related information. The project includes data preprocessing, feature engineering, model training, evaluation, and deployment using **Streamlit**.

---

# 🚀 Features

* 📊 Customer Churn Prediction
* 🤖 End-to-End Machine Learning Pipeline
* 🧹 Automated Data Preprocessing
* 🔄 Categorical Feature Encoding
* 📈 Model Evaluation
* 🌐 Interactive Streamlit Web Application
* ⚡ Real-time Customer Prediction
* 💾 Saved ML Pipeline using Joblib

---

# 🛠️ Tech Stack

## Programming Language

* Python

## Machine Learning

* Scikit-learn
* Random Forest Classifier
* Pipeline
* ColumnTransformer

## Data Analysis

* Pandas
* NumPy

## Visualization

* Matplotlib
* Seaborn

## Deployment

* Streamlit

## Model Saving

* Joblib

---

# 📂 Project Structure

```text
Ecommerce-Sales-Prediction/
│
├── app/
│   └── app.py
│
├── data/
│   ├── raw/
│   └── processed/
│
├── models/
│   └── customer_churn_pipeline.pkl
│
├── notebooks/
│   ├── 01_Data_Understanding.ipynb
│   └── 02_Model_Training.ipynb
│
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```

---

# 📈 Dataset

Dataset: **Telco Customer Churn Dataset**

The dataset contains customer demographic details, subscribed services, billing information, and churn status.

Example Features:

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges

---

# 🤖 Machine Learning Workflow

* Data Cleaning
* Missing Value Handling
* Exploratory Data Analysis (EDA)
* Feature Encoding
* Pipeline Creation
* Model Training
* Model Evaluation
* Model Serialization using Joblib
* Streamlit Deployment

---

# 📊 Model Performance

| Metric    |                    Value |
| --------- | -----------------------: |
| Algorithm | Random Forest Classifier |
| Accuracy  |                  **78%** |

---

# 🌐 Streamlit Application

The application allows users to:

* Enter customer information
* Predict churn in real time
* View churn probability
* Display prediction result instantly

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Rahul110-Bst/Ecommerce-sales-Prediction.git
```

Move into the project

```bash
cd Ecommerce-Sales-Prediction
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate the environment

**Windows**

```bash
.venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Application

```bash
streamlit run app/app.py
```

Open your browser:

```text
http://localhost:8501
```

---

# 📌 Future Improvements

* SHAP Explainability
* Batch Prediction using CSV Upload
* Feature Importance Visualization
* ROC Curve & Confusion Matrix
* Model Comparison Dashboard
* Cloud Deployment

---

# 👨‍💻 Author

**Rahul Kandwal**

GitHub: https://github.com/Rahul110-Bst

---

# ⭐ Skills Demonstrated

* Machine Learning
* Data Preprocessing
* Feature Engineering
* Model Evaluation
* Random Forest Classification
* Scikit-learn Pipeline
* Streamlit
* Joblib
* Git & GitHub
* End-to-End ML Project Development
