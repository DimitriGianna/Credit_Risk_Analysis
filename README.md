# Credit_Risk_Analysis

## Overview
Using credit card data from LendingClub, a peer-to-peer lending services company, data was analyzed using different machine learning algorithms to evaluate their performance and make recommentdations on their use in order to predict credit risk. 

## Results

### Naive Random Oversampling
![image](https://user-images.githubusercontent.com/112590378/210694736-30481832-e207-434c-ba3e-999e3ef3c032.png)

- Balanced Accuracy:  65%
- Precision:  1%/100%
- Recall: 72%/59%




### SMOTE Oversampling
![image](https://user-images.githubusercontent.com/112590378/210694868-03351dcc-83af-4318-98a0-731b4142721c.png)

- Balanced Accuracy:  66%
- Precision:  1%/100%
- Recall: 63%/69%
- 
### Undersampling 
![image](https://user-images.githubusercontent.com/112590378/210694892-2591d0f9-cf38-4b06-b1e1-b604458d9b15.png)

- Balanced Accuracy:  54%
- Precision:  1%/100%
- Recall: 69%/40%
- 
### Combination (Over and Under) Sampling
![image](https://user-images.githubusercontent.com/112590378/210694918-83b435ee-0eaa-44a6-94f0-e25b67052ba3.png)

- Balanced Accuracy:  65%
- Precision:  1%/100%
- Recall: 72%/57%

### Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/112590378/210694947-343cfcdb-4d7d-40e0-a638-2270ab083ed7.png)

- Balanced Accuracy:  79%
- Precision:  3%/100%
- Recall: 70%/87%
- 
### Easy Ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/112590378/210694978-6f17bd7a-274c-4fcc-95fa-8f15e3213b29.png)

- Balanced Accuracy:  93%
- Precision:  9%/100%
- Recall: 92%/94%

## Summary
Every machine learning algorithm did poorly in determining a high credit card risk accurately, However, the Easy Ensemble AdaBoost Classifier demonstrated a recall of 93% meaning in detects almost all high risk credit. Still, a great number of low risk credit is classified as high risk and for that reason, I would not recommend any of these models to be used to predict credit risk.


