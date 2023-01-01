# Diabetes Data Exploration

## Dataset

The diabetes dataset consist of information on females of Pima Indian Heriatage at least 21 years and older. There are 768 observation with 9 variables in the dataset. Dataset can be found [here](https://www.kaggle.com/datasets/mathchi/diabetes-data-set).

## Summary of findings

Eight explanatory features were investigated with respect to their association with diabetes outcomes. Seven out of eight explanatory features, namely, number of pregnancies, blood pressure, triceps skinfold, insulin, body mass index (BMI), diabetes pedigree function, and age were skewed. Blood glucose levels measured 2 h after the oral glucose tolerance test were normally distributed. A log transformation was applied to minimise skewness in the skewed variables.
All eight explanatory features were associated with the outcome of diabetes in 22% of the participants. Outside the main outcome of interest, a strong positive correlation was observed between BMI and triceps skinfold, glucose, and insulin levels. These correlations were expected because BMI and triceps skinfold are used to measure adiposity, and both measurements are positively correlated with adiposity. Adiposity is a known risk factor of diabetes. The correlation was further investigated, and surprisingly, patients with and without diabetes had a high BMI and triceps skinfold, and the association was not clear. Blood glucose is known to stimulate insulin production. Thus, when blood glucose levels increase, insulin production also increases. For participants with diabetes, both glucose and insulin levels were high, which may suggest resistance to insulin action. This explains why blood glucose was still high 2 h after the oral glucose tolerance test in participants with diabetes despite the high amounts of insulin observed. 


## Key Insights for presentation

For this presentation, I focused on the relationship between the eight explanatory features and the outcome of diabetes, as well as the correlation between glucose and insulin stratified by the outcome of diabetes.