# Titanic Dataset Analysis 

This project involves cleaning, analyzing, and visualizing the Titanic dataset to uncover insights related to passenger survival during the historic shipwreck.

##  Project Details

- **Dataset**: Titanic passenger data (891 rows × 12 columns)
- **Objective**: 
  - Clean the dataset by handling missing and duplicate values.
  - Perform exploratory data analysis (EDA).
  - Visualize key relationships between passenger features and survival.
  - Derive meaningful insights from the data.

##  Steps Performed

1. **Import Required Libraries**  
   Imported libraries like Pandas, NumPy, Matplotlib, and Seaborn.
2. **Load Dataset**  
   Loaded the Titanic dataset using Pandas.
3. **Data Cleaning**  
4. **Exploratory Data Analysis (EDA)**  
 
##  Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

##  Visualizations Included

- Count plots
- Scatter plots
- Box plots
- Pair plots
- Correlation heatmap

# Interview Questions

## 1. What is EDA and why is it important?

**EDA (Exploratory Data Analysis)** is the process of analyzing and visualizing datasets to understand their main characteristics, spot patterns, detect anomalies, and test hypotheses.  
It’s important because it helps clean the data, choose the right models, and make better decisions.

## 2. Which plots do you use to check correlation?

- **Heatmap** (correlation matrix)
- **Pairplot** (scatterplot matrix)
- **Scatter plots** (for individual variable pairs)

## 3. How do you handle skewed data?

- Apply **log transformation**, **square root transformation**, or **Box-Cox transformation**.
- Use **robust models** or **remove outliers** if needed.

## 4. How to detect multicollinearity?

- Check the **correlation matrix** for highly correlated features.
- Use **Variance Inflation Factor (VIF)**; a VIF greater than 5 or 10 indicates multicollinearity.

## 5. What are univariate, bivariate, and multivariate analyses?

- **Univariate analysis**: Analysis of a single variable (e.g., histogram of age).
- **Bivariate analysis**: Analysis of two variables to find relationships (e.g., scatter plot of height vs weight).
- **Multivariate analysis**: Analysis involving more than two variables simultaneously (e.g., multiple regression analysis).
- 
## 6. Difference between heatmap and pairplot?

- **Heatmap**: Displays the strength of correlation between variables using colors.
- **Pairplot**: Shows pairwise relationships with scatterplots and histograms for all combinations of variables.                                                                                      

## 7. How do you summarize your insights? (in 2 lines)

"I summarize insights by highlighting key patterns, trends, and anomalies observed in the data, backed by visualizations.  
I also mention how these findings can guide business or project decisions."
