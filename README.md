# DiabetesPrediction
Diabetes is the target variable being predicted

The Diabetes Prediction Dataset.csv file contains medical and demographic data of patients along with their diabetes status, whether positive or negative. It consists of various features such as age, gender, body mass index (BMI), hypertension, heart disease, smoking history, HbA1c level, and blood glucose level. The Dataset can be utilized to construct machine learning models that can predict the likelihood of diabetes in patients based on their medical history and demographic details.

__Gender:__ Gender refers to the biological sex of the individual, which can have an impact on their susceptibility to diabetes.

__Age:__ Age is an important factor as diabetes is more commonly diagnosed in older adults.Age ranges from 0-80 in our dataset.

__Hypertension:__ Hypertension is a medical condition in which the blood pressure in the arteries is persistently elevated.

__Heart disease:__ Heart disease is another medical condition that is associated with an increased risk of developing diabetes.

__Smoking history:__ Smoking history is also considered a risk factor for diabetes and can exacerbate the complications associated.

__BMI:__ BMI (Body Mass Index) is a measure of body fat based on weight and height. Higher BMI values are linked to a higher risk.

__HbA1c level:__ HbA1c (Hemoglobin A1c) level is a measure of a person's average blood sugar level over the past 2-3 months.

__Blood glucose level:__ Blood glucose level refers to the amount of glucose in the bloodstream at a given time. High blood glucose levels are a key.

__Diabetes:__ Diabetes is the target variable being predicted, with values of 1 indicating the presence of diabetes and 0 indicating the absence of diabetes.


# Analysing
In here we train 7 models on the data and predict the test set and then check the CAP curve.

By CAP curve we recognize that all the models have a good prediction.

At last we check the accuracy of the models and get that Random Forest Classification has the best accuracy(97 percent).
