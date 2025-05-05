# Titanic Survival Prediction 🚢

This project uses the Titanic dataset to build a machine learning model that predicts whether a passenger survived or not. It's a classic beginner-friendly data science problem based on real historical data.

## 📌 Objective
To predict the survival of passengers on the Titanic based on features like age, gender, passenger class, fare, and more.

## 🛠️ Tools & Technologies
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn (Logistic Regression, Decision Tree, KNN)
- Jupyter Notebook

## 📂 Dataset
The dataset contains information on Titanic passengers, including:
- `Pclass`: Ticket class
- `Sex`: Gender
- `Age`: Age in years
- `SibSp`: # of siblings/spouses aboard
- `Parch`: # of parents/children aboard
- `Fare`: Passenger fare
- `Embarked`: Port of Embarkation
- `Survived`: Survival (0 = No, 1 = Yes)

## 📊 Workflow
1. **Data Loading**: Load CSV data into a DataFrame.
2. **Exploratory Data Analysis (EDA)**: Analyze data distribution and missing values.
3. **Data Cleaning**: Drop irrelevant columns, handle missing values.
4. **Feature Encoding**: Convert categorical data to numerical.
5. **Model Building**: Train Logistic Regression, Decision Tree, and Support Vector classifiers.
6. **Evaluation**: Compare model accuracy and select the best-performing model.

## ✅ Results
All models were evaluated using accuracy scores. The best model can be used to predict a new passenger's survival based on their details.

## 📁 Files
- `tested.ipynb` – Main Jupyter notebook with code and output
- `README.md` – Project documentation

## 🧠 Future Improvements
- Hyperparameter tuning
- Cross-validation
- Feature engineering
- More advanced models (e.g., Random Forest, XGBoost)

## 📬 Contact
For questions or suggestions, feel free to reach out!
