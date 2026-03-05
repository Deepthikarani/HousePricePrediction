## 🏠 House Price Prediction using Machine Learning

This project implements an end-to-end Machine Learning regression pipeline to predict house prices using the Boston Housing Dataset.
The goal is to analyze how different housing features such as crime rate, number of rooms, accessibility, and tax rates influence house prices and to build a regression model capable of predicting the median value of owner-occupied homes.
The entire workflow is implemented in Jupyter Notebook following a structured Machine Learning pipeline including data analysis, preprocessing, model training, and evaluation.

## 🎯 Problem Statement

Predicting house prices accurately is a classic supervised learning regression problem with important real-world applications such as:
- Real estate price estimation
- Urban development planning
- Property investment analysis
- Market trend forecasting
The objective of this project is to train a regression model that predicts house prices based on multiple numerical housing features.

## 📊 Dataset Description

- Dataset Name: Boston Housing Dataset
- Dataset File: boston.csv
- Target Variable: MEDV (Median value of owner-occupied homes)

## Key Features
| Feature  | Description                                   |
| :--------| :---------------------------------------------|
| CRIM     | Crime rate per town                           |
| RM       | Average number of rooms per dwelling          |
| LSTAT    | Percentage of lower status population         |
| NOX      | Nitric oxide concentration                    |
| TAX      | Property tax rate                             |
| PTRATIO  | Pupil–teacher ratio                           |
| DIS      | Distance to employment centers                |

## Tech Stack
| Category                |  Tools Used                                 |
| :-----------------------| :-------------------------------------------|
| Programming Language    |  Python                                     |
| Environment             |  Jupyter Notebook                           |
| Data Processing         |  Pandas, NumPy                              |
| Visualization           |  Matplotlib, Seaborn                        |
| Machine Learning        |  Scikit-learn, XGBoost                      |

## ⚙️ Machine Learning Workflow
The project follows a structured ML development pipeline:

1️⃣ Data Loading & Understanding
- Loaded dataset from CSV file
- Inspected dataset structure and shape
- Checked for missing values

2️⃣ Exploratory Data Analysis (EDA)
- Distribution analysis of numerical features
- Correlation heatmap to understand relationships
- Identification of influential features affecting house prices

3️⃣ Data Processing
- Feature selection
- Train–test split for model validation

4️⃣ Model Building
- Implemented XGBRegressor for regression modelling

5️⃣ Model Evaluation
Model performance was evaluated using:
- R² Score
- Mean Squared Error (MSE)

6️⃣ Model Interpretation
- Feature impact analysis
- Error analysis
- Understanding bias–variance tradeoff

## 📈 Results & Performance
The trained regression model demonstrated strong predictive capability on unseen test data.
The evaluation metrics confirmed that the model successfully captures the relationships between housing features and property prices.

## 📚 Key Learnings
Through this project, the following concepts were explored:
- Importance of Exploratory Data Analysis (EDA)
- Understanding feature relationships and correlations
- Impact of multicollinearity in regression models
- Interpreting regression metrics such as R² Score and MSE
- Implementing a structured machine learning workflow

## 📂 Project Structure
```
House_Price_Prediction
|
|---House_Price_Prediction.ipynb
|   Main notebook containing the full ML pipeline
|
|---boston.csv
|   Dataset used for training the model
|
|---README.md
    Project documentation
```

## ▶️ How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/your-username/House_Price_Prediction.git

2️⃣ Navigate to the project directory
cd House_Price_Prediction

3️⃣ Launch Jupyter Notebook
jupyter notebook

4️⃣ Open and run
House_Price_Prediction.ipynb

## 🚀 Future Improvements
Potential enhancements for this project include:
- Hyperparameter tuning using GridSearchCV
- Feature engineering for non-linear relationships
- Model comparison with multiple regression algorithms
- Deploying the trained model using Flask / FastAPI
- Building an interactive Streamlit dashboard

## 👩‍💻 Author
Deepthikarani Pokali

GitHub:
https://github.com/Deepthikarani
