# CA01 – Exploratory Data Analysis: House Price Dataset

This repository contains my Exploratory Data Analysis (EDA) and data cleaning work for **CA01**. The goal of this assignment is to analyze the structure, quality, and contents of the house price training dataset and prepare it to be analytics-ready for future machine learning models.

## Dataset
- **Source:** House Price Dataset (provided for CA01)
- **File used:** `house-price-train.csv`
- Each row represents a residential property, described by numerical and categorical features related to size, quality, condition, and sale price.

## Project Overview
The analysis follows the EDA workflow covered in class and closely mirrors the logic of the Titanic EDA example.

### Part 1: Data Understanding
- Dataset structure and variable types
- Data Quality Report (missing values, uniqueness, and data types)
- Univariate analysis of the target variable (`SalePrice`)
- Bivariate analysis between key numeric features and `SalePrice`

### Part 2: Data Cleaning
- Removal of ID and extremely high-missing columns
- Missing value handling using domain logic  
  - Filling `"None"` where missing values indicate absence  
  - Median imputation for numeric variables to reduce sensitivity to skew and outliers
- Outlier identification using the IQR method (outliers are retained)

### Part 3: Collinearity Analysis
- Full numeric correlation matrix
- Identification of highly correlated feature pairs
- Discussion of multicollinearity and feature selection considerations

## Key Takeaways
- `SalePrice` is right-skewed with valid high-end outliers
- Size and quality features show the strongest relationships with price
- Missing values are mostly structural and can be handled without distorting patterns
- Several numeric features are highly correlated and should not be used together in linear models

## Files
- `CA01_Fong_Lieu.ipynb` – Main EDA and data cleaning notebook  
- `README.md` – Project overview

## Notes
This repository focuses on EDA and data preparation only. Model building and prediction are intentionally excluded and will be addressed in later assignments.
