CREDIT CARD FRAUD DETECTION

Credit Card Fraud has become a major concern with the growing use of online transactions. The aim of this project is to build a machine learning model that can identify whether a credit card transaction is genuine or fraudlent.

In this project, I used the Credit Card Fraud Detection dataset and applied Logistic Regression to classify transactions. Since the dataset contained significantly more genuine transactions than fraudlent ones, I used undersmapling to balance the data before training the model.

Technologies used:  
1.Python  
2.Pandas  
3.Numpy  
4.Scikit-learn  
5.Matplotlib  
6.Seaborn  
7.Google Colab

Dataset:  
The dataset contain credit card transactions labeled as either-  
Genuine Transaction(0) | Fraud Tansaction(1)  
Due to the significant difference between genuine and fraudulent cases, data balancing techniques were used before model training.

Workflow:  
1.Loaded and explored the dataset  
2.Checked the dataset for missing values and class distribution  
3.Separated genuine and fraudulent transactions  
4.Balanced the dataset using undersampling  
5.Split the data into training and testing sets  
6.Trained a Logistic Regression model  
7.Evaluated the model using Accuracy, Precision, Recall, F1 Score and Confusion Matrix  

Data Visualization:  
To better understand the dataset and model performance, I created the followng visualizations-  
1.Class Distribution  

<img width="1280" height="1010" alt="image" src="https://github.com/user-attachments/assets/fdf90708-4906-4423-98f2-5aa5b846726c" />

2.Balanced Class Distribution

<img width="1280" height="774" alt="image" src="https://github.com/user-attachments/assets/d8e88be3-e1cd-452e-932d-da6b7e83b934" />  


Working on this project helped me gain practical experience in:  
*Data Preprocessing  
*Handling imbalance datasets  
*Machine learning model training  
*Model evaluation techniques  
*Data Visualization  
*Fraud detection using machine learning

Conclusion:  
This project gave be better understanding of how machine learning can be used to detect fraudulent transactions. It also helped me learn the importance of data preprocessing and model evaluation while working with real-world datasets.

Notes:  
1. Imbalanced Dataset: One thing I noticed while working in this project was that fraudulent transactions made only a very small portion of the dataset compared to genuine transactions. This helped me understand how an imbalanced dataset can affect model's prediction.
2. Undersampling: Since the dataset contained signifiantly more genuine transactions than fraudulent ones, I used undersampling to reduce the number of genuine transactions. This helped create a balanced dataset and allowed the model to learn from both classes more effectively.
3. Model Evaluation:  I learned that metrics such a Precision, Recall and F1 score can provide deeper insights into model performance than accuracy alone, especially in fraud detection problem.
