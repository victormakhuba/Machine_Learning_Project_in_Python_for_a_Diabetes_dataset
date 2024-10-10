# Machine Learning Project in Python for a Diabetes dataset
Overview
In this project my aim was to develop a machine learning model using Python that predicts whether a person has diabetes or not based on the medical data.
I used a Support Vector machine (supervised learning algorithm) to classify data into diabetic and non-diabetic categories.

My workflow
I first collected the dataset which contains 768 samples (rows) and 9 features (columns), including:
1. Pregnancies
2. Glucose
3. BloodPressure
4. SkinThickness
5. Insulin
6. BMI
7. DiabetesPedigreeFunction
8. Age
9. Outcome
Secondly, I processed the data by standardizing the data using StandardScaler from Sklearn so that I could ensure all features contribute equally.
I then split the dataset into training and testing sets where 80% were training and 20% were testing using train_test_split

Thirdly, I initialized the SVM classifier and trained it using training data allowing the model to classify the data based on the provided features.

Fourthly, I evaluated the model using accuracy_score for both training and testing datasets where an accuracy score above 75% is considered good showing that the model can generalize well to new data

Lastly, i created a prediction system to allow the input of new patient data and receive predictions on whether the person is diabetic or non-diabetc.

Coding Environment
I used Jupyter on VsCode
I imported various liraries including numpy, pandas, abd sklearn


