# Predicting-Heart-Disease
Heart Disease UCI Dataset obtained from UCI machine learning repository. 
Dataset: HeartDiseaseData.csv 
Url https://archive.ics.uci.edu/ml/datasets/Heart+Disease

Neural network to predict the severity of heart failure based on various medical and demographic parameters.

This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. 
In particular, the Cleveland database is the only one that has been used by ML researchers to
this date. The "goal" field refers to the presence of heart disease in the patient. It is integer valued from 0 (no presence) to 4.
Dataset description:

  Age: number
  
  Sex: Binary
  
  Cp: chest pain type (1 = typical angina; 2 = atypical angina; 3 = non-anginal pain; 4 = asymptomatic)
  
  Trestbps: resting BP (in mm HG)
  
  Cholesterol: serum cholestrol in mg/dl
  
  Fbs: fasting blood sugar > 120mg/dl (1=yes)
  
  RestECG: 0 = normal; 1 = having ST-T; 2 = hypertrophy
  
  Thalach: max heart rate achieved
  
  Exang: exercise induced angina (1 = yes; 0 = no)
  
  Oldpeak: ST depression induced by exercise relative to rest
  
  Slope: slope of the peak exercise 
  
  Ca: number of major vessels (0-3) colored by flourosopy
  
  Thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

  num0 = level 0 heart failure (no HF)
  num1 = level 1 heart failure
  num2 = level 2 heart failure
  num3 = level 3 heart failure
  num4 = level 4 heart failure (most severe)

Output: severity of heart failure on a scale of 0-4, with 0 being no HF, and 4 being the heighest severity of HF.
