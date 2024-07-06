# Census-income
Income prediction plays a crucial role in understanding economic trends and assisting in financial planning. Our project utilizes the Census Income dataset from the UCI Machine Learning Repository, which contains income information for over 48,000 individuals from the 1994 US census. The objective is to predict whether an individual earns more than $50,000 a year based on various demographic and socio-economic attributes.

**Problem Statement-** In this project, our goal is twofold: Preprocess the dataset to ensure clean and usable data. Develop an understanding of the dataset through exploratory analysis and visualizations. With these insights, we will perform a classification task to predict whether an individual's income exceeds $50,000 using different machine learning algorithms.

**Steps Undertaken-**
1. Importing Data: We loaded the dataset using Pandas.
2. Data Cleaning: We handled missing values, corrected data types, and performed other preprocessing steps to ensure data quality.
3. Data Analysis: We explored the dataset to understand the distribution of features and their relationships.
4. Exploratory Data Analysis (EDA): Using Matplotlib and Seaborn, we created visualizations to identify patterns and key insights within the data.
5. Model Building: We built and evaluated predictive models using Logistic Regression, Decision Tree, and Random Forest algorithms.

**Results-** We used three different machine learning algorithms to predict the response variable (income level):

1. Logistic Regression: Achieved an accuracy of 0.786
2. Decision Tree: Achieved an accuracy of 0.788
3. Random Forest: Achieved an accuracy of 0.839

Among these models, the Random Forest algorithm outperformed the others, providing the highest accuracy in predicting whether an individual's income exceeds $50,000.

**Conclusion-** The Random Forest model proved to be the best for this classification task, thanks to its ability to handle complex interactions between features and reduce overfitting. This model can be instrumental for policymakers and businesses in making informed decisions based on income predictions.
