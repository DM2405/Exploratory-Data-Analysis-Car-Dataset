# Used Car Price Analysis – EDA

This project performs a complete Exploratory Data Analysis (EDA) on a used car dataset to understand the factors affecting car resale prices.  
The analysis includes data cleaning, visualization, insights, and conclusion using Python.

## Dataset
The dataset contains information about used cars such as:
- Car name
- Year of purchase
- Selling price
- Present price
- Kilometers driven
- Fuel type
- Seller type
- Transmission type
- Number of previous owners

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Steps Performed

### 1. Data Loading & Understanding
- Loaded dataset using Pandas
- Checked shape, data types, missing values, and duplicates

### 2. Data Cleaning
- Removed unnecessary columns
- Converted **Year** into **Car Age**
- Encoded categorical variables
- Ensured data consistency

### 3. Exploratory Data Analysis (EDA)
- Distribution analysis of selling price and mileage
- Relationship analysis using scatter plots
- Category-wise analysis (Fuel type, Transmission, Seller type)
- Correlation heatmap (numeric features only)
- Advanced plots like pair plots, box plots, and violin plots

### 4. Key Insights
- Selling price decreases as car age and kilometers driven increase
- Diesel and automatic cars generally have higher resale value
- Present price is the strongest predictor of selling price
- First-owner cars tend to sell at higher prices


## Visualizations Included
- Histograms
- Scatter plots
- Box plots
- Pair plots
- Correlation heatmap

Each visualization is accompanied by a clear explanation of what it represents.

## Conclusion
The dataset is clean, well-structured, and suitable for regression-based machine learning models.  
Key factors influencing car resale value include **present price, car age, fuel type, transmission, and mileage**.

## Future Work
- Build machine learning models for price prediction
- Feature importance analysis
- Model performance comparison




