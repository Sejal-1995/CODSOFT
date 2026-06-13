#BIG MART SALES PREDICTION DATASET

This project focuses on predicting product sales for Big Mart outlets using Machine Learning. The goal is to analyze various product and outlet characteristics and build a model that can estimate future sales with good accuracy.
The project includes data preprocessing, handling missing values, data visualization, feature encoding, model training, and performance evaluation.

Dataset Features:  
* Item Identifier
* Item Weight
* Item Fat Content  
* Item Visibility
* Item Type
* Item MRP
* Outlet Identifier
* Outlet Establishment Year
* Outlet Size
* Outlet Location Type
* Outlet Type
  
Target Variable:
* Item Outlet Sales

What I Worked On:  
* Loaded and explored the dataset using Pandas to understand the data and identify potential issues
* Handled missing values by filling:  
       *Item Weight with the mean value.  
       *Outlet Size with the most frequent value.
* Performed exploratory data analysis (EDA) to find trends and relationships between different features and sales
* Created visualizations using Matplotlib and Seaborn to better understand customer and outlet behavior
* Converted categorical columns into numerical values using Label Encoding so they could be used by machine learning models
* Trained a Random Forest Regressor model to predict sales based on product and outlet information
* Evaluated the model using MAE, RMSE, and R² score to measure prediction accuracy
* Used the trained model to generate sales predictions for new products 

Tools Used:  
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

Working on this project helped me get practical experience with:  
* Data cleaning and preprocessing
* Handling missing values
* Exploratory Data Analysis (EDA)
* Feature engineering and encoding
* Training machine learning models
* Evaluating regression models
* Interpreting model results and predictions

Model Performance:  
* Mean Absolute Error(MAE): 761.99
* Root Mean Squared Error(RMSE): 1092.96
* R2 Score: 0.5605

Overall, this project gave me a practical understanding of the complete machine learning workflow, from cleaning and exploring data to training and evaluating a predictive model. I learned how to handle missing values, work with different types of data, create meaningful visualizations, and apply machine learning algorithms to solve a real-world business problem. It also helped me improve my skills in Python and data analysis while understanding how data-driven insights can be used to predict sales and support business decisions. Most importantly, I gained hands-on experience turning raw data into useful predictions and insights.

Notes:  
At first, I considered using Linear Regression because it’s simple and easy to interpret. But after exploring the data, I noticed that the relationship between features like Item MRP, Item Visibility, Outlet Type, and Sales wasn’t strictly linear. There were clear non-linear patterns and interactions that a linear model couldn’t capture well.

So I switched to Random Forest Regressor, which handled the complexity much better by combining multiple decision trees. It was able to capture non-linear relationships and also reduce overfitting. The main challenge was that Random Forest is less interpretable compared to Linear Regression, and tuning parameters like the number of trees and depth required some trial and error. Overall, even though it was slightly more complex, it gave better accuracy and more reliable predictions for this dataset.
