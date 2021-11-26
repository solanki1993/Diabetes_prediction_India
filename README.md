# Diabetes_prediction_India
Diabetes Prediction using Machine Learning. Dataset used: PIMA Indians Diabetes dataset from Kaggle.
There are estimated 72.96 million cases of diabetes in adult population of India. The prevalence in urban areas ranges between 10.9% and 14.2% and prevalence in rural India was 3.0-7.8% among population aged 20 years and above with a much higher prevalence among individuals aged over 50 years (INDIAB Study).

Early prediction is therefore paramount in preventing the disease.

The dataset used  consist of several medical predictor (independent) variables and one target (dependent) variable, Outcome.

Independent variables include the number of pregnancies the patient has had, their BMI, insulin level, age, skin thickness, glucose level, blood pressure, diabetes pedigree.

correlation is found between each independent variables and the missiing zero values in the predictor columns are checked too.

Used SimpleImputer to fill misssing values and the algorithm used is - RandomforestClassifier, with which an accuracy of 76% is achieved.
Hyperparameter tuning is done as well using RandomizedSearchCV

Classsifier Used is the XGBClassifier()
cross validation is done , score is obtained and the mean of the score is obtained.
