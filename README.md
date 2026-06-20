# 🏠 House Price Prediction

## 📌 Project Overview

This project predicts house prices using Machine Learning based on different property features such as area, number of bedrooms, bathrooms, stories, parking, and other amenities.

The project includes data preprocessing, data visualization, model training, model evaluation, and feature analysis.

---

## 🎯 Objective

- Predict house prices using regression models.
- Compare the performance of Linear Regression and Random Forest Regressor.
- Identify the features that have the greatest impact on house prices.

---

## 📂 Dataset

- **Dataset:** Housing Prices Dataset
- **Source:** Kaggle
- **File:** `Housing.csv`

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📋 Project Workflow

1. Load and explore the dataset.
2. Check for missing values and duplicate records.
3. Convert categorical features into numerical values.
4. Split the dataset into training and testing sets.
5. Train:
   - Linear Regression
   - Random Forest Regressor
6. Evaluate models using:
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R² Score
7. Visualize the results.
8. Analyze feature importance and summarize the findings.

---

## 📊 Visualizations

The project includes:

- Distribution of House Prices
- Correlation Heatmap
- Actual vs Predicted House Prices
- Feature Importance Chart

---

## 📈 Model Performance

| Model | R² Score |
|--------|---------:|
| Linear Regression | 0.653 |
| Random Forest Regressor | 0.612 |

The Linear Regression model performed slightly better than the Random Forest model for this dataset.

---

## 🔍 Key Findings

- Area is the most important feature affecting house prices.
- Bathrooms, parking, stories, and air conditioning also influence the price.
- Most houses fall within the medium price range.
- Machine learning can help estimate house prices more accurately.

---

## 📁 Project Structure

```
HousePricePrediction/
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
├── README.md
└── charts/
    ├── house_price_distribution.png
    ├── correlation_heatmap.png
    ├── actual_vs_predicted.png
    └── feature_importance.png
```

---

## 👩‍💻 Author

**Syed Uzma Farzeen**

B.Tech Information Technology
