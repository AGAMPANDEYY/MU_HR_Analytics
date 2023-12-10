## To further analyze the dataset and Predict Employee Attrition using ML model.

First, we worked on Pre-Processing the dataset,

- Category encoding was used to create Numeric values for important columns such as Education Field, Department
- SMOTE teachnique was used to work upon the imbalanced dataset.
- Standard Scaler was use to normalise all field values between 0 and 1
- Logistic Regression and Random Forest Classifier models were used to make prediction
  
  ### The results of each model:

- Logistic Regression(Without SMOTE train dataset)- 85.48% Accuracy and F1 score-- (Attrition No)0.92 and (Attrition Yes)0.0
  
  <img src="https://github.com/AGAMPANDEYY/MU_HR_Analytics/assets/94832116/38cee7fd-85a1-4cb6-8cb8-f67b35d0769b" width="700" height="300">
- Random Forest Classifier- 91.38% Accuracy and F1 Score --(Attrition No)0.95 and (Attrition Yes)0.60
  <img src="https://github.com/AGAMPANDEYY/MU_HR_Analytics/assets/94832116/27869054-6db4-40ca-bfd6-aba712d23ab6" width="700" height="300">
- Logistic Regression (SMOTE Balanced train Dataset)- 58.95% (Decrease in Accuracy) and F1 score (Attrition No)0.70 and (Attrition Yes)0.34
  <img src="https://github.com/AGAMPANDEYY/MU_HR_Analytics/assets/94832116/5cb5ac26-bc41-40b3-a389-aaa27cbe1d4f"
 width="700" height="300">  
