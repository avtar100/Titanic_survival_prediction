# 🛳️ Titanic Survival Prediction (Kaggle ML Project)

This beginner-friendly project predicts the survival of passengers on the Titanic using machine learning — specifically, Logistic Regression. The dataset is sourced from the famous [Kaggle Titanic competition](https://www.kaggle.com/competitions/titanic).

---

## 🎯 Objective

To build a machine learning model that predicts whether a passenger survived or not, based on features like age, gender, class, and fare.

---

## 📁 Files in this Project

| File                | Description                                         |
|---------------------|-----------------------------------------------------|
| `titanic_model.ipynb` | Jupyter Notebook with all code and explanations    |
| `submission.csv`      | Final output predictions for Kaggle submission     |
| `README.md`           | Project overview and instructions (this file)      |

---

## 📦 Dataset Used

From: [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data)

- `train.csv`: training data with labels (Survived)
- `test.csv`: test data without labels
- `submission.csv`: prediction output from the trained model

> 📝 Note: `train.csv` and `test.csv` are not uploaded due to size. You can download them directly from Kaggle.

---

## 🧠 Features Used for Prediction

- `Pclass` - Passenger class (1st, 2nd, 3rd)
- `Sex` - Gender (encoded as 0 = female, 1 = male)
- `Age` - Age (missing values filled with mean)
- `SibSp` - Siblings/Spouses aboard
- `Parch` - Parents/Children aboard
- `Fare` - Ticket fare (missing values filled)
- `Embarked` - Port of Embarkation (encoded as 0, 1, 2)

---

## 🛠️ Tech Stack

- Python 3.x
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Workflow

1. Data Cleaning & Preprocessing
2. Feature Engineering
3. Train/Test Split
4. Model Training (Logistic Regression)
5. Accuracy Evaluation
6. Final Prediction on `test.csv`
7. Export to `submission.csv`

---

## ✅ Model Performance

Achieved ~**80% accuracy** on the validation set using Logistic Regression.

---

## 📤 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
   cd titanic-survival-prediction
