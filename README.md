# LAI-and-LST-Analysis-with-Python
This project investigates the long-term relationship between vegetation cover and land surface temperature (LST) using time-series data for India and China.

The primary goal is to understand whether changes in vegetation influence surface temperature and to compare this relationship between two major countries with different climatic and land-use patterns.

## 🎯 Problem Statement

> To analyze the relationship between vegetation cover (LAI) and land surface temperature (LST) over time for India and China, and to determine whether changes in vegetation have a statistically significant impact on surface temperature trends.

## ❓ Key Research Questions

- Does an increase in vegetation density reduce land surface temperature?
    
- Is the LAI–LST relationship statistically significant?
    
- How does this relationship differ between India and China?
    
- Are there increasing or decreasing long-term trends in LAI and LST?

## 🛠️ Tools & Technologies Used

- **Python**
    
- **Libraries**:
    
    - `pandas`, `numpy` – data handling
        
    - `matplotlib`, `seaborn` – visualization
        
    - `scikit-learn` – linear regression modeling
        
    - `statsmodels` – OLS statistical regression
        
    - `scipy` – statistical tests
 
## 🔄 Methodology

### 1️⃣ Data Preparation

- Loaded and cleaned time-series data
    
- Converted year column to integer format
    
- Checked for missing values and handled them using mean imputation
    

### 2️⃣ Exploratory Data Analysis (EDA)

- Descriptive statistics
    
- Pair plots and correlation heatmaps
    
- Bar plots and time-series visualizations
    

### 3️⃣ Statistical Modeling

- **Simple Linear Regression** (Scikit-learn) to quantify LAI–LST relationships
    
- **Ordinary Least Squares (OLS)** regression (Statsmodels) for statistical inference
    
- Interpreted coefficients, intercepts, R² values, and p-values
    

### 4️⃣ Assumption Validation

- Normality testing using **Shapiro–Wilk test**
    
- Histogram and QQ plot visualization
    

### 5️⃣ Trend Analysis

- Polynomial trend fitting
    
- Detection of increasing or decreasing trends in LAI and LST over time

## 📈 Key Results & Insights

- A **negative relationship** was observed between LAI and LST, indicating a **cooling effect of vegetation**.
    
- The relationship was **stronger in India** compared to China.
    
- Regression coefficients suggest that an increase in LAI leads to a decrease in land surface temperature.
    
- Normality tests confirmed that the data distribution does not significantly deviate from normality.
