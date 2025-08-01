# 🚢 Titanic Survival Prediction

A beginner-friendly machine learning project to predict whether a Titanic passenger survived or not, using basic passenger information.

## 📊 Features Used
- Pclass (Ticket Class)
- Sex (Gender)
- Age
- Fare

## 🛠️ Tools & Technologies
- Python
- Pandas & NumPy (Data handling)
- Scikit-learn (Modeling & Evaluation)
- Random Forest Classifier

## 📌 Workflow
1. Load and clean dataset (fill missing values, encode categorical data)
2. Select important features
3. Train-test split (80/20)
4. Train a Random Forest Classifier
5. Evaluate with accuracy, confusion matrix, and classification report

## ✅ Results
- Achieved ~80% accuracy
- Balanced performance across both classes
- Demonstrates basic ML workflow on structured data

## 🚀 Future Improvements
- Use more features (e.g., Embarked, SibSp, Parch)
- Try other models (Logistic Regression, SVM, XGBoost)
- Hyperparameter tuning (GridSearchCV)
- Add cross-validation

## 📂 Dataset
- [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)  
- File used: `train.csv`

## 📎 How to Run
1. Clone the repo  
2. Add `train.csv` to the project folder  
3. Run the script in Jupyter Notebook or any Python IDE

```bash
pip install pandas numpy scikit-learn
python titanic_model.py
