# Credit_Risk_Analysis

## Overview

While credit resk can be hard to determine, we have data in this project that we used to condlude if someone is high or low risk. 

Results
Naive Random Oversampling results: 
<img width="955" alt="Screen Shot 2022-04-24 at 1 51 15 PM" src="https://user-images.githubusercontent.com/95730129/164994571-2011c040-ddf2-400d-8bf4-34573258e81e.png">

SMOTE oversampling results: 
<img
     width="955" alt="2" src="https://user-images.githubusercontent.com/95730129/164994589-dbacec2c-e24c-4837-992b-ab3cb259aa59.png">

Undersampling results:
<img width="955" alt="3" src="https://user-images.githubusercontent.com/95730129/164994602-62da178e-7857-4822-955b-634030ed454b.png">

Combination(over and undersampling) results:<img width="955" alt="4" src="https://user-images.githubusercontent.com/95730129/164994614-9a48891f-a3da-43f5-b2cf-27e5cd65f3b2.png">

Balanced Random Forest Classifier results:
<img width="955" alt="5" src="https://user-images.githubusercontent.com/95730129/164994622-4760ea87-88d0-430a-8dc1-5578ba9392ef.png">

Easy Ensemble AdaBoost Classifier results: 
<img width="955" alt="6" src="https://user-images.githubusercontent.com/95730129/164994629-815b9241-c993-4d47-b83c-9c022e841c61.png">

## Summary

In our first four models our accuracy score is not as high as the ensemble classifiers and the recall in the oversampling/undersampling/mixed models is low as well. I recommend the ensemble classifiers. It appears that the Easy Ensemble had the best balance of all the models.
