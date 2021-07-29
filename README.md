# Diabetes Prediction
The task of predicting, if a person might have diabetes or not has been accomplished in this repository with the help of machine learning algorithms.

## Dataset
PIMA Indian Diabetes dataset has been used as the input data for predicting if a pers
on is diabetec or not. 
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

Below given is a sample data from the dataset.
![image](https://user-images.githubusercontent.com/32951163/127432633-00a281e1-73b2-4536-bde4-15f647ad447e.png)

The data has 768 rows and 10 columns in total with one 9 predictor variable and one target outcome. Below given is a sample data from the dataset.

The different predictors present in the dataset are 'num_preg', 'glucose_conc', 'diastolic_bp', 'thickness', 'insulin','bmi', 'diab_pred', 'age', 'skin', 'diabetes'.

Columns | Description
--- | ---
num_preg | Number of times pregnant
glucose_conc | Plasma glucose concentration a 2 hours in an oral glucose tolerance test
diastolic_bp | Diastolic blood pressure (mm Hg)
thickness    | Triceps skin fold thickness (mm)                                       insulin      | 2-Hour serum insulin (mu U/ml)
bmi          | Body mass index (weight in kg/(height in m)^2)
diab_pred    | Diabetes pedigree function
| age          | Age (years)
skin       
| diabetes     | Class variable (0 or 1) 268 of 768 are 1, the others are 0

## Algorithms
3 different algorithms has been used to do the prediction. All are tree based ensemble models. Below given are the algorithms along with their corresponding accuracy levels:

**Algorithm** | **Accuracy Score**
--- | ---
**Decission Tree Classifier** | 68%
**Random Forest Classifier** | 75%
**XGBoost Classifier** | 76%
