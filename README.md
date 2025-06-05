🛍️ Black Friday Sales Prediction
This project analyzes and models purchase behavior using the Black Friday dataset to predict customer spending. The dataset is provided by a retail company and is commonly used for regression modeling tasks.

📁 Dataset Overview
Source: Kaggle - Black Friday Sales Prediction

Rows: ~550,000

Columns: 12

Target Variable: Purchase — amount spent by a customer

🔑 Key Features
Column Name	Description
User_ID	Unique ID for each customer
Product_ID	Unique ID for each product
Gender	Gender of the customer
Age	Age group of customer
Occupation	Type of job/occupation
City_Category	Tier/category of the city
Stay_In_Current_City_Years	Years spent in current city
Marital_Status	0 = Single, 1 = Married
Product_Category_1	Main product category
Product_Category_2	Secondary category (nullable)
Product_Category_3	Tertiary category (nullable)
Purchase	🎯 Target: Purchase amount in local currency

🎯 Objective
Analyze customer demographics and behavior.

Handle missing values and categorical features.

Train a regression model to predict purchase amount.

Evaluate model accuracy on unseen data (test set).

🧪 Train/Test Split
We divide the data as follows:

train.csv → Used to build and train machine learning models.

test.csv → Used to evaluate model performance. It contains all columns except Purchase.

🔧 Tech Stack
Language: Python 3

Libraries:

Pandas, NumPy (data handling)

Matplotlib, Seaborn (visualization)

Scikit-learn, XGBoost, LightGBM (modeling)

🔍 Exploratory Data Analysis (EDA)
Distribution of purchases by gender, age, and city category

Correlation between product categories and purchase amount

Handling of missing values in Product_Category_2 and Product_Category_3

