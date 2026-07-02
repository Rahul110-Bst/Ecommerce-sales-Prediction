# 📊 End-to-End E-commerce Customer Churn Prediction

An end-to-end Machine Learning project that predicts whether an e-commerce customer is likely to churn based on customer demographics, subscribed services, contract details, and billing information.

The project covers the complete Machine Learning workflow, including data preprocessing, feature engineering, model comparison, model evaluation, and deployment using **Streamlit**.

---

# 🚀 Features

- 📊 Customer Churn Prediction
- 🤖 End-to-End Machine Learning Pipeline
- 🧹 Automated Data Preprocessing
- 🔄 Missing Value Handling
- 🔤 Categorical Feature Encoding
- 📈 Model Comparison
- 🎯 Best Model Selection
- 💾 Saved ML Pipeline using Joblib
- 🌐 Interactive Streamlit Web Application
- ⚡ Real-Time Prediction
- 📉 Churn Probability Prediction

---

# 🛠️ Tech Stack

## Programming Language

- Python

## Machine Learning

- Scikit-learn
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier
- Pipeline
- ColumnTransformer

## Data Analysis

- Pandas
- NumPy

## Data Preprocessing

- SimpleImputer
- OneHotEncoder
- StandardScaler

## Deployment

- Streamlit

## Model Serialization

- Joblib

## Version Control

- Git
- GitHub

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

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains customer demographic information, subscribed services, contract details, billing information, and churn status.

### Features Used

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract
- Paperless Billing
- Payment Method
- Monthly Charges
- Total Charges

### Target Variable

- Churn (Yes / No)

---

# 🤖 Machine Learning Workflow

- Data Cleaning
- Missing Value Handling
- Feature Selection
- Data Preprocessing
- Feature Scaling
- Categorical Encoding
- Pipeline Creation
- Train-Test Split
- Model Training
- Model Evaluation
- Model Comparison
- Best Model Selection
- Model Serialization
- Streamlit Deployment

---

# 🧠 Machine Learning Models

The following machine learning models were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

After comparing all models, the **best-performing model** was selected and saved using **Joblib** for deployment.

---

# 📊 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **80.38%** |
| Random Forest | 78.75% |
| XGBoost | 76.90% |
| Decision Tree | 73.06% |

**Best Model:** Logistic Regression

---

# 🌐 Streamlit Application

The Streamlit application allows users to:

- Enter customer details
- Predict customer churn instantly
- View churn probability
- Get real-time prediction results through a simple user interface

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone https://github.com/Rahul110-Bst/Ecommerce-sales-Prediction.git
```

Move into the project directory

```bash
cd Ecommerce-Sales-Prediction
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate the virtual environment

### Windows

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

# 📷 Application Preview

You can add screenshots of the Streamlit application here.

Example:

```text
README Images/
├── home.png
├── prediction.png
```

Then use:

```markdown
![Home](images/home.png)

![Prediction](images/prediction.png)
```

---

# 📌 Future Improvements

- SHAP Explainability
- Batch Prediction using CSV Upload
- Feature Importance Visualization
- ROC Curve
- Confusion Matrix Visualization
- Hyperparameter Tuning
- Cloud Deployment (Render / Streamlit Cloud)
- Docker Support
- REST API using FastAPI

---

# 👨‍💻 Author

**Rahul Kandwal**

GitHub: https://github.com/Rahul110-Bst

---

# ⭐ Skills Demonstrated

- Machine Learning
- Classification Algorithms
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Data Preprocessing
- Feature Engineering
- Pipeline Creation
- Model Evaluation
- Model Comparison
- Streamlit
- Joblib
- Git
- GitHub
- End-to-End ML Project Development

---

# 📄 License

This project is licensed under the MIT License.