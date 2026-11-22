# 📱 Mobile Phone Price Prediction using Simple Linear Regression

## 📌 Project Overview

This project predicts mobile phone prices using **Simple Linear Regression**, a supervised machine learning algorithm.

The model uses **RAM (GB)** as the input feature to estimate a mobile phone's price. It was developed using Python, Pandas, Matplotlib, and Scikit-learn, with a smartphone dataset.

The project demonstrates the complete machine learning workflow, from data preprocessing and visualization to model training, evaluation, and prediction.

## 🎯 Objective

- Understand and implement Simple Linear Regression.
- Analyze the relationship between RAM and mobile phone prices.
- Clean and preprocess the dataset.
- Train a machine learning model using Scikit-learn.
- Evaluate model performance using regression metrics.
- Predict the price of a phone using its RAM capacity.

## 📊 Dataset

- **Dataset:** Smartphones Dataset
- **Source:** Kaggle
- **Original records:** 1,816
- **Selected features:** RAM, Final Price
- **Records after preprocessing:** 1,333 (as recorded in the notebook)

### Selected Columns

| Column | Description |
|---|---|
| RAM | RAM capacity of the smartphone |
| Final Price | Price of the smartphone (target variable) |

Missing RAM values were removed before model training.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

## 🔄 Machine Learning Workflow

1. Import required Python libraries.
2. Load the smartphone dataset.
3. Inspect dataset structure and missing values.
4. Select RAM and Final Price columns.
5. Clean the dataset by removing missing values.
6. Perform exploratory data analysis (EDA).
7. Visualize the relationship between RAM and price.
8. Split the dataset into training and testing data.
9. Train the Simple Linear Regression model.
10. Predict prices on test data.
11. Evaluate the model using regression metrics.
12. Predict the price for a new phone with 8 GB RAM.

## 🤖 Model Details

**Algorithm:** Simple Linear Regression

- Input feature (X): RAM
- Target variable (y): Final Price
- Training data: 80%
- Testing data: 20%
- Random state: 42

The model learns a linear relationship between RAM and phone price.

### Regression Equation

ŷ = mX + c

Where:

- ŷ = Predicted price
- m = Slope / coefficient
- X = RAM capacity
- c = Intercept

## 📈 Model Evaluation Results

The trained model achieved the following results on the test dataset:

| Metric | Result |
|---|---:|
| MAE (Mean Absolute Error) | 118.27 |
| MSE (Mean Squared Error) | 28,086.83 |
| RMSE (Root Mean Squared Error) | 167.59 |
| R² Score | 0.5579 |

### Interpretation

- The MAE indicates an average absolute prediction error of approximately 118.27 price units.
- The RMSE is 167.59, reflecting prediction errors while penalizing larger errors more heavily.
- The R² score of 0.5579 indicates that RAM explains approximately 55.79% of the variation in mobile phone prices in the test dataset.

## 🔮 Sample Prediction

The trained model was used to predict the price of a mobile phone with 8 GB RAM.

| RAM | Predicted Price |
|---|---:|
| 8 GB | 544.20 |

*This is a model-generated estimate in the dataset's price units, not a verified market price.*

## 📉 Limitations

This model uses only RAM as an input feature. Mobile phone prices are also affected by:

- Brand
- Storage capacity
- Processor
- Camera quality
- Display specifications
- Other hardware and market factors

Therefore, the model cannot accurately distinguish between budget and premium smartphones having the same RAM capacity.

## 🚀 Future Improvements

- Use Multiple Linear Regression with additional features.
- Include storage, brand, processor, and other specifications.
- Compare different regression algorithms.
- Improve model performance through feature engineering.
- Develop an interactive web application for price prediction.

## 📚 Learning Outcomes

Through this project, I learned:

- Fundamentals of supervised machine learning.
- Data cleaning and preprocessing.
- Exploratory data analysis.
- Feature selection.
- Training and testing machine learning models.
- Simple Linear Regression implementation.
- Regression model evaluation.
- Making predictions on new data.

## 👨‍💻 Author

**Shubham Sonawane**

AI & Data Science Engineering Student

---

⭐ This project was developed as part of my Machine Learning practical learning to understand and implement Simple Linear Regression using Python.
