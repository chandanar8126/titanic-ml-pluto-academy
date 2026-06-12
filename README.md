# Titanic Survival Prediction — Machine Learning Model

## About This Project
This project is part of the Pluto Academy AI & ML Internship Program (Project 02).
I built, trained and evaluated 3 machine learning models to predict survival 
of Titanic passengers and identified the best performing model.

## Dataset
- Source: [Titanic Dataset — Kaggle](https://www.kaggle.com/c/titanic)
- Rows: 891 passengers
- Features: Passenger class, age, gender, fare, embarked, and more

## Tools Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Google Colab

## Project Structure
- `Titanic_ML_PlutoAcademy.ipynb` — Main notebook with full analysis
- `README.md` — Project overview

## What I Did
1. Loaded and preprocessed the dataset (handled missing values, encoded categoricals)
2. Performed feature engineering using correlation analysis
3. Trained 3 different ML models (Logistic Regression, Random Forest, KNN)
4. Compared all 3 models using Accuracy, Precision, Recall and F1 Score
5. Identified Random Forest as best model with confusion matrix and conclusion

## Model Comparison Results

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---|---|---|---|
| Logistic Regression | 0.8101 | 0.7857 | 0.7432 | 0.7639 |
| Random Forest | 0.8212 | 0.8088 | 0.7432 | 0.7746 |
| KNN | 0.7039 | 0.6842 | 0.5270 | 0.5954 |

## Best Model
**Random Forest** performed best with 82.12% accuracy. It outperformed 
other models because it combines 100 decision trees which reduces 
overfitting and captures complex patterns in the data.

## Key Findings
- Gender (Sex) was the strongest predictor of survival
- Higher class passengers had significantly better survival chances
- Random Forest outperformed both Logistic Regression and KNN
- KNN struggled due to features having very different value ranges

## Internship
- Program: Pluto Academy AI & ML Internship
- Website: plutoacademy.in
