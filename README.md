## Life Expectancy Analysis using Machine Learning

# Project Overview
This project analyzes global life expectancy data to identify key health and socio-economic factors influencing life expectancy. It applies Exploratory Data Analysis (EDA) and machine learning models to predict trends and generate actionable business insights for public health decision-making.

---

# Objectives
- Analyze global life expectancy patterns across countries and years  
- Identify key drivers such as mortality rates, immunization, alcohol consumption, and health expenditure  
- Build and evaluate machine learning models for prediction  
- Translate model outputs into meaningful business and policy insights  

---

# Dataset
- **Source:** Life Expectancy Data (CSV)
- **Records:** Country-wise data across multiple years
- **Key Features:**
  - Life expectancy
  - Adult mortality
  - Infant deaths
  - Alcohol consumption
  - Hepatitis B immunization
  - Health expenditure
  - GDP, schooling, BMI (where applicable)

---

# Data Preprocessing
- Handled missing values using appropriate statistical methods
- Removed duplicates and inconsistent records
- Converted categorical variables into usable formats
- Scaled numerical features for model performance
- Selected relevant features based on correlation and importance

---

# Exploratory Data Analysis (EDA)
- Descriptive statistics to understand data distribution
- Correlation analysis between life expectancy and predictors
- Trend analysis across years and regions
- Visualizations:
  - Histograms & boxplots
  - Correlation heatmaps
  - Scatter plots for key feature relationships

---

# Modeling
- **Target Variable:** Life Expectancy (numeric)
- **Models Used:**
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting
  - XGBoost (if available)
- **Train-Test Split:** 80% training, 20% testing

---

# Model Evaluation
- **Evaluation Metrics:**
  - RMSE
  - MAE
  - R² Score
- Residual analysis to check model errors and stability
- Feature importance analysis to identify top predictors

---

# Results
- Machine learning models successfully captured life expectancy patterns
- Key influential factors:
  - Adult mortality
  - Infant deaths
  - Immunization coverage
  - Health expenditure
  - Education-related indicators
- Best model achieved strong predictive performance with acceptable error rates

---

# Business Insights
- Developing countries lag due to lower healthcare spending and education levels
- Immunization and primary healthcare investments yield high ROI
- Education (especially female schooling) has long-term positive health impacts
- Data-driven prioritization helps policymakers allocate resources effectively

---

# Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Streamlit (for interactive interface)
- Jupyter Notebook

---

# How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/life-expectancy-analysis.git ```
2.	Install dependencies
```
pip install -r requirements.txt
 ```
4.	Run the application or notebook
```
 streamlit run app.py
 ```
or open the Jupyter Notebook

---
# Author
Shruti Khadtar

# License
This project is for academic and learning purposes.
