# Medical-Insurance-Cost-Prediction
🏥 Medical Insurance Cost Prediction Using Machine Learning

📌 Project Overview
This project focuses on building a Machine Learning model to predict the medical insurance cost for individuals based on various personal and lifestyle-related factors. Insurance companies require accurate cost estimations to determine fair premiums, while individuals can gain insights into how their health and habits affect their insurance expenses. The model is implemented using a supervised learning algorithm — Linear Regression, which is ideal for predicting continuous outcomes.

📊 Dataset Description
The dataset includes the following features:

age: Age of the individual

sex: Gender (male/female)

bmi: Body Mass Index

children: Number of children

smoker: Smoking status (yes/no)

region: Residential region in the U.S.

charges: Medical insurance cost (target variable)

🔗Dataset Link: https://www.kaggle.com/datasets/mirichoi0218/insurance

🔁 Workflow
1. Data Loading & Exploration
Load the dataset using pandas

Explore data with descriptive statistics and visualizations using matplotlib and seaborn

2. Data Preprocessing
Handle categorical variables using one-hot encoding

Separate features (X) and target (y)

3. Train-Test Split
Split the dataset into training and testing sets using train_test_split from sklearn

4. Model Training
Train a Linear Regression model using the training data

5. Model Evaluation
Evaluate the model using:

Mean Squared Error (MSE)

R-squared (R²) Score

6. Prediction
Use the trained model to predict insurance charges from new, raw input data

✅ Conclusion
This project demonstrates the application of machine learning in the healthcare and insurance domain for cost prediction. It lays the foundation for more advanced predictive models and real-world deployment scenarios that can support insurance providers and individual financial planning.
