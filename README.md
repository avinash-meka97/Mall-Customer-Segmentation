This project focuses on segmenting mall customers based on a dataset from market analysis. The main objective is to explore the factors influencing customer spending and develop data-driven strategies to increase sales.
Key Objectives:
1.Understanding Spending Score Factors: Investigate how factors like gender, age, and income affect the spending score.
2.Segmentation for Target Marketing: Cluster customers into segments based on their spending patterns and income to help the marketing team target the right audience.
3.Sales Optimisation: Leverage insights from customer behaviour to devise strategies that boost sales.
Data Features:
Customer Data: The dataset includes five variables: customer ID, gender, age, annual income, and spending score (ranging from 1 to 100).
Segmentation: Customers are grouped based on spending scores and income levels, categorized into low, average, and high spenders/income earners.
Methods and Techniques:
1.Exploratory Data Analysis (EDA):
Visualisations using ggplot2 include bar plots, density plots, and box-plots to analyse gender distribution, age groups, and income levels.
Key insights: Female shoppers tend to have higher spending scores, and middle-aged groups (30-40 years old) have higher annual income.
2.Clustering:
K-means clustering is used to segment customers based on their annual income and spending scores. Five distinct clusters were identified, helping to categorise customers into different spending behaviour groups.
3.Linear Regression:
Models were developed to predict spending scores based on age, income, and other factors.
Key insights: There is a significant correlation between annual income and spending score, confirming that higher income is associated with higher spending.
4.Boosted Tree Modeling:
A boosted tree model was applied to predict spending scores and optimise marketing strategies based on income, age, and gender. Model performance was measured using Root Mean Square Error (RMSE) to evaluate accuracy.
