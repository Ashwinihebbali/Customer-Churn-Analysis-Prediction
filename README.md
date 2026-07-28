# Customer Churn Prediction Analysis 

## 📌 Project Overview
Customer churn prediction is a machine learning project that identifies customers who are likely to stop using a company's services. This project uses the **Telco Customer Churn** dataset to preprocess data, train a machine learning model, and evaluate its performance for predicting customer churn.

---

## 🚀 Features
- Data loading and exploration
- Data preprocessing and cleaning
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Train-test data splitting
- Random Forest model training
- Model prediction
- Performance evaluation
- Confusion matrix visualization

---
## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Workflow

### 1. Data Import
- Load required libraries.
- Read the Telco Customer Churn dataset.

### 2. Data Exploration
- Check missing values.
- Understand dataset statistics.
- Analyze churn distribution.

### 3. Data Preprocessing
- Convert TotalCharges to numeric values.
- Handle missing values.
- Encode categorical features.
- Split dataset into training and testing sets.
- Scale numerical features.

### 4. Model Training
Train a **Random Forest Classifier** using the training dataset.

### 5. Prediction
Predict customer churn on the testing dataset.

### 6. Model Evaluation
Evaluate the model using:
- Accuracy Score
- Confusion Matrix

---
## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

2. Install the required libraries.

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

3. Place the dataset (`Telco-Customer-Churn.csv`) in the project folder.

4. Open the notebook.

```bash
jupyter notebook Customer_Churn_Prediction_Analysis.ipynb
```

5. Run all cells.

---

## 📌 Results
The Random Forest model predicts whether a customer is likely to churn based on customer demographics, account information, and service usage. Performance is evaluated using accuracy and a confusion matrix.

---

## 🔮 Future Improvements
- Hyperparameter tuning
- Compare multiple ML algorithms
- Feature importance analysis
- ROC-AUC evaluation
- Deploy using Streamlit or Flask
- Real-time churn prediction

## ⭐ If you found this project useful, don't forget to give it a Star!
