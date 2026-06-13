#SALES PREDICTION DATASET

This project focuses on predicting product sales based on advertising expenditures across different marketing channels. The goal is to analyze how spending on TV, Radio, and Newspaper advertisements influences sales and build a machine learning model that can accurately estimate future sales. The project includes data exploration, visualization, model training, performance evaluation, and sales prediction using Linear Regression.

Dataset Features:  
* TV Advertising Budget  
* Radio Advertising Budget  
* Newspaper Advertising Budget  
  
Target Variable:
* Sales

What I Worked On:  
* Loaded and explored the dataset using Pandas to understand the data structure and identify any potential issues.
* Checked for missing values and verified the dataset quality before model training.  
* Performed exploratory data analysis (EDA) to understand the relationships between advertising channels and sales.  
* Created visualizations using Matplotlib and Seaborn to observe trends, correlations, and feature distributions.
* Split the dataset into training and testing sets to evaluate model performance on unseen data.  
* Trained a Multiple Linear Regression model using TV, Radio, and Newspaper advertising budgets as input features.
* Evaluated the model using Mean Squared Error (MSE) and R² Score.
* Analyzed the model coefficients to understand the impact of each advertising channel on sales.
* Used the trained model to predict sales for a new advertising budget scenario.

Tools Used:  
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

What I Learned:  
* Understood how Linear Regression can be used to model relationships between multiple independent variables and a target variable.
* Gained experience in performing exploratory data analysis and identifying feature relationships.
* Improved my understanding of regression evaluation metrics such as Mean Squared Error (MSE) and R² Score.
* Learned how model coefficients can be interpreted to understand feature influence on predictions.

Data Visualization:  
1. Sales Distribution:
   <img width="1280" height="788" alt="image" src="https://github.com/user-attachments/assets/1916b533-3514-4642-90ec-55e81545ad3f" />
  Distribution of Item Outlet Sales across all products.  

2. Outlet vs Sales:
    <img width="1280" height="936" alt="image" src="https://github.com/user-attachments/assets/dd257133-4c1d-45b8-b508-eec4639a5cfe" />
  This suggests that outlet type has a strong influence on overall sales performance.  

3. Feature Importance:
    <img width="1280" height="710" alt="image" src="https://github.com/user-attachments/assets/9934ec3d-a475-48cb-abf3-ecdbe128e5a9" />
  Item MRP is the most important feature, followed by outlet type, while other features have relatively lower impact on predictions.
   
Model Performance:  
* Mean Squared Error(MSE): 1092.96
* R2 Score: 0.5605

Conclusion:  
Overall, this project provided hands-on experience with the complete machine learning workflow, from data exploration and visualization to model training and evaluation. I learned how advertising expenditure can influence product sales and how Linear Regression can be used to quantify these relationships. The project improved my understanding of predictive analytics, feature interpretation, and regression modeling. It also strengthened my Python, data analysis, and machine learning skills while demonstrating how data-driven insights can support marketing and business decisions.

Notes:  
For this project, I selected Multiple Linear Regression because the goal was to understand and predict sales based on numerical advertising expenditures across multiple channels. Linear Regression is well-suited for modeling the relationship between continuous input variables and a continuous target variable.
One of the advantages of using Linear Regression is its simplicity and interpretability. The model coefficients clearly show how changes in TV, Radio, and Newspaper advertising budgets affect predicted sales. During the analysis, TV and Radio advertising appeared to have a stronger influence on sales, while Newspaper advertising contributed less significantly.

Overall, this project helped me gain practical experience in regression analysis, model evaluation, and interpreting machine learning results in a business context.
