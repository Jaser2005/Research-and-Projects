# Research-and-Projects
# Diabetes Prediction using Machine Learning

This project predicts the likelihood of diabetes in patients using machine learning algorithms such as Logistic Regression, Random Forest, and XGBoost.

## 📊 Dataset
The dataset used is the Pima Indians Diabetes Database from Kaggle/UC Irvine Repository.

## 🧠 Workflow
1. Data Preprocessing (handling missing values, scaling)
2. Exploratory Data Analysis (EDA)
3. Model Training and Evaluation
4. Hyperparameter Tuning using GridSearchCV
5. Model Saving and Visualization

## 🧩 Models Used
- Logistic Regression (baseline)
- Random Forest Classifier
- XGBoost Classifier

## 📈 Results
- Best Model: Random Forest (tuned)
- Accuracy: 0.87
- ROC AUC: 0.91

## 🧰 Tech Stack
- Python
- scikit-learn
- XGBoost
- Pandas, NumPy
- Matplotlib, Seaborn

## 🧾 How to Run
```bash
pip install -r requirements.txt
python src/train_model.py
