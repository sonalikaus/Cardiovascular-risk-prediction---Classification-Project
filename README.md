# Cardiovascular-risk-prediction---Classification-Project
Supervised Classification Project


The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.

Variables Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors.



This project's key contribution was the use of cutting-edge machine learning techniques to construct an understandable medical prediction system for the detection of heart disease. In order to forecast the outcome, the machine learning models learns patterns from the features present in the existing dataset and
applies them to the unknown dataset. Classification is one of the effective 
machine learning methods for making predictions. When trained with the right data, classification is a supervised machine learning technique that successfully recognises the disease.

we performed some Feature Engineering in the form of dealing with wrong datatype, attempt to remove multicollinearity, and created a new column named MAP(Mean Arterial Pressure) by combining existing two columns sysBP and diaBP
![map](https://user-images.githubusercontent.com/109536544/195515248-1bb5fc13-75c7-4854-86ab-b4f5315ac43b.PNG)  ![download](https://user-images.githubusercontent.com/109536544/195514402-b5c6202d-3699-4153-bff2-4cade24be5c9.png)


In the next step, we created a total of 8 Classification Models in the form of Logistic Regression, Decision Tree, KNN, Random Forest, Gradient Boosting, XGBoost, Naïve Bayes and Support Vector Classifier.

In the final step, we tried to evaluate all the above models with the help of Evaluation Metrics such as Accuracy, Precision, Recall, Specificity, F1 score, and ROC value. Also, ROC AUC Curve of all the model was plotted at the end in which highest average area under the curve (AUC) of 0.96 is attained by Gradient Boost Classifier and second highest is of 0.94 attained by Support Vector Classifier and XG Boost.    
![Capture](https://user-images.githubusercontent.com/109536544/195515362-844dab92-ee29-4659-a239-b657120ec7cc.PNG)   ![Capture 1](https://user-images.githubusercontent.com/109536544/195515380-a283b305-6e1e-4954-adea-83be7c52fc71.PNG)


