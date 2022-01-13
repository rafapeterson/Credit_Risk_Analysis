# Credit_Risk_Analysis
## Overview
The purpose of this analysis was to compare different sampling methods to determine the most accurate predictive modeling for credit card risk. The dataset from LendingClub was utilized, with the target column being the lending risk of the applicant. 
## Results
In order to determine the best method for sampling, the following methods were tested:<br> <br>
**Naive Random Oversampling** <br>![image](https://user-images.githubusercontent.com/13009587/149406112-84f29ad2-187a-4d12-8331-c3dbac3fe651.png)
<br>**SMOTE Oversampling**<br> ![image](https://user-images.githubusercontent.com/13009587/149405647-cde361d2-6cd2-4264-906b-d871e92ca189.png)
<br>**Undersampling** <br> ![image](https://user-images.githubusercontent.com/13009587/149405827-1aafde36-2f2e-48bc-8186-0bfdbdeb9cb5.png)
<br> **Combination (SMOTEENN)** <br> ![image](https://user-images.githubusercontent.com/13009587/149405591-45bd5144-c85f-4233-8a01-fe1e4f234218.png)
<br> **Balanced Random Forest Classifier** <br> ![image](https://user-images.githubusercontent.com/13009587/149405444-f25cd6e5-2eb4-4c2a-9cc5-58ff5b217c47.png)

<br> & finally, **Easy Ensemble AdaBoost Classifier.** <br> ![image](https://user-images.githubusercontent.com/13009587/149405509-650a0c00-c2d0-4d3e-a094-545a72b77a97.png)
<br>

## Summary
Based on the data, the ensemble classifiers' balanced accuracy scores were the highest, with ~76% vs. ~66% for the others. Therefore, I would recommend sticking with an ensemble model for the most accurate results. 
