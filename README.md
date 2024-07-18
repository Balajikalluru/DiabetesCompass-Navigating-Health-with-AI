# DiabetesCompass-Navigating-Health-with-AI

This project aims to predict diabetes using machine learning techniques on a dataset containing various health-related attributes. The model helps identify individuals at risk of diabetes based on factors such as pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, age, and family history.

#### Dataset
The dataset includes the following features:

Pregnancies: Number of pregnancies<br/>
Glucose: Plasma glucose concentration after a glucose tolerance test<br/>
BloodPressure: Diastolic blood pressure<br/>
SkinThickness: Triceps skin fold thickness<br/>
Insulin: 2-hour serum insulin level<br/>
BMI: Body mass index<br/>
Age: Age in years<br/>
DiabetesPedigreeFunction: Likelihood of diabetes based on family history<br/>
Outcome: 0 (no diabetes) or 1 (diabetes)<br/>

#### Data Preprocessing
Handling Missing Values: Replaced zeros in Glucose, BloodPressure, SkinThickness, Insulin, and BMI columns with mean or median values, depending on the distribution.<br/>
#### Data Transformation: 
Applied QuantileTransformer to normalize the data.<br/>
#### Exploratory Data Analysis
Visualized the distribution of features and the correlation between them.<br/>
Identified that Glucose, BMI, and Age are the most correlated with the Outcome.

### Model Training
Linear Regression: Achieved an accuracy of 79.22%. <br/>
Logistic Regression: Achieved an accuracy of 79.00% 

### Conclusion
The project successfully demonstrates the use of machine learning to predict diabetes. Logistic Regression provided a good balance between simplicity and accuracy. Further improvement can be achieved by experimenting with other models and hyperparameter tuning.
