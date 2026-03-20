# House Price Prediction using Linear Regression

## Problem Statement
A real estate company **HomeVista Properties** operates across multiple cities
and handles thousands of residential property sales every year. The company
wants to automate its house pricing process using Machine Learning to predict
the market price of a house based on its physical features, location, and condition.

## Objective
Build a regression model that accurately predicts house prices using historical
property data by performing data analysis, preprocessing, training a Linear
Regression model, and evaluating its performance.

## Dataset Description
Each row represents one residential house with its physical, location, and
construction details.

| Feature | Description |
|---|---|
| Id | Unique identification number for each house |
| MSSubClass | Type of dwelling involved in the sale |
| MSZoning | General zoning classification of the sale |
| LotArea | Lot size in square feet |
| LotConfig | Lot configuration (Inside, Corner, Cul-de-sac, etc.) |
| BldgType | Type of dwelling (1Fam, 2Fam, Duplex, Townhouse, etc.) |
| OverallCond | Overall condition rating of the house (scale 1–10) |
| YearBuilt | Original construction year |
| YearRemodAdd | Year the house was remodeled or additions were made |
| Exterior1st | Exterior covering on house |
| BsmtFinSF2 | Type 2 finished square feet of basement |
| TotalBsmtSF | Total square feet of basement area |
| **SalePrice** | **Target variable — Final selling price of the house** |

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

## Approach
1. Exploratory Data Analysis (EDA)
2. Data Preprocessing (handling missing values, encoding categorical features)
3. Feature Selection
4. Model Training using Linear Regression
5. Model Evaluation (R² Score, MAE, RMSE)

## How to Run
1. Clone the repository
```
   git clone https://github.com/mishthygupta/house-price-prediction.git
```
2. Install dependencies
```
   pip install -r requirements.txt
```
3. Open the notebook
```
   jupyter notebook house_price_predictor.ipynb
```

## Results
| Metric | Score |
|---|---|
| R² Score | 0.3741421796138532 |
| MAE | 30829.93666432187 |
| RMSE | 41138.55870230105 |

## Author
**Mishthy Gupta**
