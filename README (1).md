# 🏦 Loan Risk Classification using Logistic Regression

This project applies **Logistic Regression** to predict whether a loan applicant is likely to default or not, based on historical data.  
It demonstrates a complete **machine learning workflow** — from data preprocessing to model evaluation — using Python.

---

## 📊 Project Overview

Financial institutions often need to assess the **creditworthiness** of loan applicants.  
This project builds a **classification model** that predicts loan default risk using logistic regression.

**Key Objectives:**
- Clean and preprocess raw loan data
- Train and test a logistic regression model
- Evaluate the model using performance metrics
- Interpret model predictions for practical use

---

## 🧠 Technologies Used

- **Python 3.x**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib / Seaborn** (for visualization)

---

## ⚙️ Workflow

1. **Data Loading:** Import dataset and explore features  
2. **Data Preprocessing:** Handle missing values, encode categorical data, and scale numeric features  
3. **Model Training:** Apply logistic regression to training data  
4. **Model Evaluation:** Measure accuracy, precision, recall, F1-score, and ROC-AUC  
5. **Predictions:** Use the model to predict risk for new applicants

---

## 📈 Results Summary

- Model used: `LogisticRegression()`
- Evaluation metrics: Accuracy, Confusion Matrix, ROC-AUC
- The model achieved strong classification performance for identifying high-risk applicants.

---

## 🧩 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/loan-risk-classification.git
   cd loan-risk-classification
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook loan-risk-classification.ipynb
   ```

---

## 📦 Dependencies

Create a `requirements.txt` file with:
```
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
```

---

## 📚 Future Improvements

- Try other algorithms: Decision Tree, Random Forest, XGBoost  
- Hyperparameter tuning  
- Deploy model using Flask or Streamlit  

---

## 👨‍💻 Author

**Amogh Jain**  
📍 Mechanical Engineer | Aspiring Business Analyst  
📧 [YourEmail@example.com]  
🔗 [LinkedIn Profile]  

---

## 🏁 License

This project is licensed under the MIT License — feel free to use and modify it.
