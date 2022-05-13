# About this project 

Every day we get more information (or data) and one of the sectors that has begun to store and analyze data is the health sector, because of the need to carry out prevention and save lives. The advantage of a large amount of data is that it is possible to have a much more coherent and precise prediction. However, the simple fact of having data is not enough; it is of vital importance to perform an exploratory data analysis (EDA). For the data to be useful, it must be cleaned, eliminating or modifying possible errors. This is where EDA plays a very important role and is a preliminary activity to find patterns or model data.

### Heart Disease Analysis 💓

Heart disease is one of the most dangerous and silent diseases suffered by human beings. Various situations or diseases can cause heart problems. Sometimes the symptoms are invisible (silent) but the problem is there and can get worse as time goes by. It can even affect some other functionalities of the human body. Sometimes a single technique used does not determine what is the root or the real problem, which means that rigorous tests must be carried out and, at the same time, the diagnoses and treatments used become a challenging task. Therefore, by requiring human intervention to determine certain criteria, an imprecise diagnosis may be incurred. 

🤖 Prediction must be more accurate than intuition 🦾

## Heart Disease Prediction with Python and Machine Learning  

This project is focused on predicting which people are more likely to suffer from heart disease based on the information presented in the attributes. Data preparation and prediction is based on the work done by algorithms in conjunction with historical data.

In this project the target variable is categorical, therefore the algorithms will be categorical, such as:

- Logistic regression
- Support vector classifier
- K Neighbors Classifier
- Nonlinear ML algorithms
- Decision tree classifier
- Random Forest Classifier
- Gradient Boosting Classifier

At the end, each algorithm has an accuracy score and they are compared against each other to determine which one has higher accuracy.



### Dataset
The dataset has 14 atrributes:

Attributes    |  Description
------------- | -------------
age | age
sex | 0 = Female, 1= Male
cp | Chest pain type (4 values) -> 0 = Typical angina; 1 = Atypical angina; 2 = non-angina pain; 3 = asymptomatic
trestbps | Resting blood pressure
chol | Serum cholestoral in mg/dl
fbs | Fasting blood sugar > 120 mg/dl
restecg | Resting electrocardiographic results (values 0,1,2)
thalach | Maximum heart rate achieved
exang | Exercise induced angina
Oldpeak | ST depression induced by exercise relative to rest
slope | The slope of the peak exercise ST segment
ca | Number of major vessels (0-3) colored by flourosopy
thal | 0 = normal; 1 = fixed defect; 2 = reversable defect
targer | 0 = less chance of heart attack, 1 = more chance of heart attack 

- Link dataset: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

**You must have installed:**

- Pandas
- Seaborn
- Sklearn
