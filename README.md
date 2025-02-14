# House Pricing Analysis

## Project Overview
This project analyzes housing prices using a dataset from Kaggle. The analysis includes data preprocessing, exploratory data analysis (EDA), hypothesis testing, and predictive modeling using Multiple Linear Regression and Random Forest Regression.

## Dataset
The dataset used in this project is obtained from [Kaggle](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset/data). It contains 13 attributes for 545 properties, including price, area, bedrooms, bathrooms, stories, location, parking space, and more.

## Steps of Analysis

### 1. Data Preprocessing
- Handled missing values and duplicates
- Verified data types and encoded categorical variables

### 2. Exploratory Data Analysis (EDA)
- Histograms, box plots, and bar charts were used to understand data distribution
- Correlation analysis using a heatmap

### 3. Hypothesis Testing
- **Chi-Square Test**: Checked dependency between categorical features
- **ANOVA Test**: Examined impact of air conditioning on price

### 4. Model Building
- **Multiple Linear Regression**: Achieved an R² score of 68.2%
- **Random Forest Regression**: Achieved an R² score of 54.4%
- Concluded that Multiple Linear Regression performed better in predicting house prices

## Results
- Area has the strongest correlation with price
- Features like air conditioning and preferred location significantly impact house prices
- The dataset's distribution was right-skewed, requiring transformations for better model performance

## Technologies Used
- Python (pandas, numpy, seaborn, matplotlib, scikit-learn)
- Jupyter Notebook
- GitHub for version control

## How to Run
1. Clone the repository:
   ```
   git clone https://github.com/pratima-bankar/House_pricing_analysis.git
   ```
2. Run the Jupyter Notebook to analyze data:
   ```
   jupyter notebook House_Pricing_Analysis.ipynb
   ```
## Contributors
- **Pratima Bankar**
- **Kashmira Mahesh Sawant**
- **Diya Deepak Makwana**
