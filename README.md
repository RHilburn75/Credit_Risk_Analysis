# Credit_Risk_Analysis

# Overview

  The purpose of the analysis was to create a supervised machine learning model that could predict credit risk. To complete this analysis, 6 different methods were used:
   1. Naive Random Oversampling
   2. SMOTE Oversampling
   3. Cluster Centroid Undersampling
   4. SMOTEENN Sampling
   5. Balanced Random Forest Classifying
   6. Easy Ensemble Classifying
  
  After going through each one of these methods, the results of the data were split into fields:
   - Training / testing datasets
   - accuracy scores
   


# Results

## Naive Random Oversampling
  * Accuracy Score: 67.3%
  * Precision High Risk: 1%
  * Precision Low Risk: 100%
  * Recall High Risk: 66%
  * Recall Low Risk: 68%

![image](https://user-images.githubusercontent.com/94253815/160261037-4d524a80-af29-4966-be6c-944f5e768258.png)



## SMOTE Oversampling
  * Accuracy Score: 67.3%
  * Precision High Risk: 1%
  * Precision Low Risk: 100%
  * Recall High Risk: 70%
  * Recall Low Risk: 64%
  
![image](https://user-images.githubusercontent.com/94253815/160261050-e1efe037-90ea-4191-8181-47ef280bd829.png)



## Cluster Centroid Undersampling
  * Accuracy Score: 51.1%
  * Precision High Risk: 0%
  * Precision Low Risk: 100%
  * Recall High Risk: 58%
  * Recall Low Risk: 44%
  
![image](https://user-images.githubusercontent.com/94253815/160261063-148ae998-3e50-455b-9954-95bb9391efe0.png)
  


## SMOTEENN Sampling
  * Accuracy Score: 68.1%
  * Precision High Risk: 1%
  * Precision Low Risk: 100%
  * Recall High Risk: 76%
  * Recall Low Risk: 60%
  
![image](https://user-images.githubusercontent.com/94253815/160261080-8e5d5c07-651e-4f04-9d0e-7e277e70f733.png)



## Balanced Random Forest Classifying
  * Accuracy Score: 64.8%
  * Precision High Risk: 56%
  * Precision Low Risk: 100%
  * Recall High Risk: 30%
  * Recall Low Risk: 100%
  
![image](https://user-images.githubusercontent.com/94253815/160261151-1a6823a9-816a-446a-ab1a-0d093039c731.png)



## Easy Ensemble Classifying
  * Accuracy Score: 92.2%
  * Precision High Risk: 6%
  * Precision Low Risk: 100%
  * Recall High Risk: 91%
  * Recall Low Risk: 94%
  
![image](https://user-images.githubusercontent.com/94253815/160261230-dacd124c-05f2-4db1-a01e-3c09f15995a2.png)



# Summary
   After conducting the analysis, the models that scored the highest in accuracy scores were the following:
    * Easy Ensemble Classifying - 92.2%
    * SMOTEENN Sampling - 68.1%
    * Naive Random Oversampling & SMOTE Oversampling tied with a score of - 67.3
   While overall, this is the most important data to follow , as this shows how it scored overall
 
   Low risk category would also be a good indicator and a metric to follow. Here are the two that scored the highest:
    * Balanced Random Forest Classifying - 100%
    * Easy Ensemble Classifying - 94%
   These two had the lowest recall risk out of all 6 models. As we look into low risk , we also have to look and see what is also the opposite side of the spectrum and that is high risk. 
   
   Let us see what had the highest recall risk:
   * Easy Ensemble Classifying - 91%
   * SMOTEENN Sampling - 76%
   
   Overall, looking at all the models and how they scored, I would recommned using the Easy ensemble Classifying  model to predict high risk loans.  It has shown to be the most accurate out of all the models.
   
   
  
