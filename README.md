Titanic Dataset Exploratory Data Analysis (EDA)

This repository contains an exploratory data analysis of the Titanic dataset using Python libraries such as Pandas, Matplotlib, Seaborn, and Plotly. The goal is to understand the dataset, check for missing values, visualize distributions, and explore relationships between features.

Steps Performed:

1. Dataset Upload
- The Titanic dataset (Titanic-Dataset.csv) is uploaded into Google Colab.

2. Libraries Used
- Pandas for data manipulation and analysis.
- Matplotlib and Seaborn for static visualizations like histograms, boxplots, heatmaps, and pairplots.
- Plotly Express for interactive visualizations.

3. Data Inspection
- Viewing first few rows using df.head().
- Checking data types and completeness with df.info().
- Summary statistics for numeric features using df.describe().
- Identifying missing values with df.isnull().sum().

4. Data Visualization
- Histograms to see distribution of numeric features.
- Boxplots to identify outliers and feature spread.
- Pairplots to examine relationships between numeric features.
- Correlation heatmap to visualize correlations between numeric variables.
- Interactive scatter plot of Age vs Fare, colored by Survived, using Plotly.

5. Key Insights
- Numeric feature distributions and potential outliers are clearly visible.
- Correlation heatmap highlights strong and weak relationships between numeric variables.
- Interactive scatter plot shows patterns of age and fare with respect to survival.

How to Run:
1. Open this repository in Google Colab.
2. Upload the Titanic-Dataset.csv file.
3. Run the EDA code to generate visualizations and insights.

Libraries Required:
pandas
matplotlib
seaborn
plotly
