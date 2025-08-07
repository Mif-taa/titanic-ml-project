# titanic-ml-project
# Titanic - Machine Learning from Disaster 🚢

This project is a solution to the [Kaggle Titanic competition](https://www.kaggle.com/competitions/titanic), which is a classic binary classification task: **predicting whether a passenger survived the Titanic shipwreck or not** using historical data.

## 📌 Problem Statement

Build a predictive model that answers the question: **"What sorts of people were more likely to survive?"** using passenger data (name, age, gender, class, etc.).

---

## 🔍 Dataset

- **Train.csv** – training data containing features and the target `Survived`.

Features include:
- `Pclass` – Ticket class (1st, 2nd, 3rd)
- `Sex` – Gender
- `Age` – Age
- `SibSp`, `Parch` – Family relations aboard
- `Fare` – Ticket fare
- `Embarked` – Port of Embarkation

---

## 🚀 Models Used

The following models were trained and evaluated:
- ✅ Logistic Regression
- 🌲 Decision Tree
- 🌳 Random Forest

Model performance was measured using **accuracy score** and **cross-validation**.

---

## 📊 Feature Engineering

- Missing values handled (`Age`, `Embarked`)
- Categorical variables encoded (`Sex`, `Embarked`)
- Feature scaling where applicable

---

## 🧪 Evaluation

- Accuracy scores on validation data
- Confusion matrices
- Cross-validation scores
  
---

## 📁 Folder Structure
Titanic_EDA_Project/
│
├── titanic_model.ipynb # Main Kaggle notebook
├── train.csv # Training dataset
└── README.md # Project documentation


---

## 📈 Sample Results

| Model             | Accuracy (Validation) |
|------------------|------------------------|
| Logistic Regression | ~80% |
| Decision Tree       | ~81% |
| Random Forest       | ~83% |

---

## ✅ Future Improvements

- Try more advanced models (e.g., XGBoost, SVM)
- Hyperparameter tuning (GridSearchCV)
- Use ensemble techniques

---

## 🧠 Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training and Evaluation
- Kaggle Submission Pipeline

---

## 🙋‍♂️ Author

**Miftahul Jannat Rishta**  
3rd-year CSE student | Interested in ML & Web Dev  
🔗 [LinkedIn](https://www.linkedin.com/in/YOUR_LINK)  
🐱 [GitHub](https://github.com/YOUR_USERNAME)  

---

## 📌 Note

This is a beginner-friendly project suitable for improving your ML workflow understanding. Contributions are welcome!

