# Credit_Risk_Analysis

## Overview of the Analysis

The purpose of this analysis is to create a model to predict whether someone is low or high credit risk based on a dataset of many variables. To accomplish this task, I used Resampling Models, a SMOTEENN algorithm, and Ensemble Classifiers to predict credit risk by individual.

## Results

* Naive Random Oversampling: The balanced accuracy score for this model is 66.3%, the precision score is 99%, and the recall is 60%. 

![Naive Random Oversampling](https://user-images.githubusercontent.com/104707395/224120025-3cd7bffc-2139-4c83-8275-b7ed57bc2ac0.png)

* Smote Oversampling: The balanced accuracy score for this model is 64.4%, the precision score is 99%, and the recall is 69%.

![Smote Oversampling](https://user-images.githubusercontent.com/104707395/224120086-26c042ab-8654-464a-a758-aeffc15bdc33.png)

* Undersampling: The balanced accuracy score for this model is 66.3%, the precision score is 99%, and the recall is 40%.

![Undersampling](https://user-images.githubusercontent.com/104707395/224120129-b69e88d5-4e0c-47b5-b015-e459423c3396.png)

* Combination Over and Undersampling: The balanced accuracy score for this model is 54.4%, the precision score is 99%, and the recall is 57%.

![combination over and undersampling](https://user-images.githubusercontent.com/104707395/224120159-9abaeac2-f425-4821-a074-79687ac800f7.png)

* Balanced Random Forest Classifier: The balanced accuracy score for this model is 79.2%, the precision score is 99%, and the recall is 88%.

![balanced random forest](https://user-images.githubusercontent.com/104707395/224120187-e88b6336-9b7a-4090-8a51-d7389bf152b8.png)

* Naive Random Oversampling Classifier: The balanced accuracy score for this model is 91.8%, the precision score is 99%, and the recall is 94%.

![Naive Random Oversampling](https://user-images.githubusercontent.com/104707395/224120207-e153ad26-4865-4231-9c8f-899d8fba5a14.png)

## Summary

Overall, the ensemble classifier models performed the best when predicting credit risk. This is evidenced by high balanced accuracy, precision, recall, and F1 scores. The Easy Ensemble AdaBoost Classifier model performed the best out of all models that we performed.  
