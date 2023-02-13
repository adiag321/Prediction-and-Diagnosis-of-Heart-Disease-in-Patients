# <p align = 'center'>Prediction and Diagnosis of Heart Disease in Patients</p>

## PROJECT OVERVIEW

This is multivariate type of dataset which means providing or involving a variety of separate mathematical or statistical variables, multivariate numerical data analysis. It is composed of 14 attributes which are age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise induced angina, oldpeak — ST depression induced by exercise relative to rest, the slope of the peak exercise ST segment, number of major vessels and Thalassemia. 

This database includes 76 attributes, but all published studies relate to the use of a subset of 14 of them. The Cleveland database is the only one used by ML researchers to date. One of the major tasks on this dataset is to predict based on the given attributes of a patient that whether that particular person has a heart disease or not and other is the experimental task to diagnose and find out various insights from this dataset which could help in understanding the problem more.

## PURPOSE

Every day, the average human heart beats around 100,000 times, pumping 2,000 gallons of blood through the body. Inside your body there are 60,000 miles of blood vessels.

The signs of a woman having a heart attack are much less noticeable than the signs of a male. In women, heart attacks may feel uncomfortable squeezing, pressure, fullness, or pain in the center of the chest. It may also cause pain in one or both arms, the back, neck, jaw or stomach, shortness of breath, nausea and other symptoms. Men experience typical symptoms of heart attack, such as chest pain , discomfort, and stress. They may also experience pain in other areas, such as arms, neck , back, and jaw, and shortness of breath, sweating, and discomfort that mimics heartburn.
It’s a lot of work for an organ which is just like a large fist and weighs between 8 and 12 ounces.

## DATA DESCRIPTION

The dataset is collected from UCI Repository  - <a href = 'https://archive.ics.uci.edu/ml/datasets/Heart+Disease'>https://archive.ics.uci.edu/ml/datasets/Heart+Disease</a>

1. age: The person’s age in years
2. sex: The person’s sex (1 = male, 0 = female)
3. cp: chest pain type
a) Value 0: asymptomatic
b) Value 1: atypical angina
c) Value 2: non-anginal pain
d) Value 3: typical angina
4. trestbps: The person’s resting blood pressure (mm Hg on admission to the hospital)
5. chol: The person’s cholesterol measurement in mg/dl
6. fbs: The person’s fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)
7. restecg: resting electrocardiographic results
a) Value 0: showing probable or definite left ventricular hypertrophy by Estes’ criteria
b) Value 1: normal
c) Value 2: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
8. thalach: The person’s maximum heart rate achieved
9. exang: Exercise induced angina (1 = yes; 0 = no)
10. oldpeak: ST depression induced by exercise relative to rest (‘ST’ relates to positions on the ECG plot. See more here)
11. slope: the slope of the peak exercise ST segment:
a) 0: downsloping
b) 1: flat
c) 2: upsloping
12. ca: The number of major vessels (0–3)
13. thal: A blood disorder called thalassemia Value 0: NULL (dropped from the dataset previously
a) Value 1: fixed defect (no blood flow in some part of the heart)
b) Value 2: normal blood flow
c) Value 3: reversible defect (a blood flow is observed but it is not normal)
14. target: Heart disease (1 = no, 0= yes)

The dataset was created by:
1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.

## METHODS

We completed the project with the following steps:

1. Performing `Exploratory Data Analysis` (EDA)
2. `Visualizing` the data
3. `Preprocessing` the Data (One-Hot encoding)
4. Machine Learning models -
* Logistic regression
* Decision Trees
5. Evaluating `Model Performance`

## CONCLUSION

1. The Area under the ROC curve is 87.09% which is somewhat satisfactory.
2. The model predicted with 86.88% accuracy. The model is more specific than sensitive.
