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
1. Pair Plot Analysis:
  <img width="1097" height="573" alt="image" src="https://github.com/user-attachments/assets/1d051866-1590-4b74-804e-b25971ebc128" />
  <img width="1218" height="661" alt="image" src="https://github.com/user-attachments/assets/8ba42369-14d6-49ef-be06-2a3f843ad1fa" />

  The visualization shows that TV and Radio advertising have a stronger positive relationship with sales, while Newspaper advertising has a weaker impact.    

2. Actual vs Predicted Sales:
    <img width="1049" height="666" alt="image" src="https://github.com/user-attachments/assets/5fb34454-146c-4b4c-b5e8-8e657ef7eef6" />

  This plot helps evaluate the model’s accuracy by comparing actual and predicted sales values.
   
Model Performance:  
* Mean Squared Error(MSE): 2.908
* R2 Score: 0.9059

Conclusion:  
Overall, this project provided hands-on experience with the complete machine learning workflow, from data exploration and visualization to model training and evaluation. I learned how advertising expenditure can influence product sales and how Linear Regression can be used to quantify these relationships. The project improved my understanding of predictive analytics, feature interpretation, and regression modeling. It also strengthened my Python, data analysis, and machine learning skills while demonstrating how data-driven insights can support marketing and business decisions.

Notes:  
For this project, I selected Multiple Linear Regression because the goal was to understand and predict sales based on numerical advertising expenditures across multiple channels. Linear Regression is well-suited for modeling the relationship between continuous input variables and a continuous target variable.
One of the advantages of using Linear Regression is its simplicity and interpretability. The model coefficients clearly show how changes in TV, Radio, and Newspaper advertising budgets affect predicted sales. During the analysis, TV and Radio advertising appeared to have a stronger influence on sales, while Newspaper advertising contributed less significantly.

Overall, this project helped me gain practical experience in regression analysis, model evaluation, and interpreting machine learning results in a business context.
