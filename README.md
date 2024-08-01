# Credit-Risk-Classification

The purpose for this analysis is to identify the creditworthiness of borrowers using what is called a Logistic Regression model, first with the original data and later with resampled training data to optimize the model.  The financial information consisted of various features including loan size, interest rate, borrow income, etc.  These features will help predict the likeliness a borrower will default on their issued loan.  

Results

Machine Learning Model 1:
  - Accuracy
    - According to the confusion matrix the accuracy is 99%

  - Precision
    - The precision of 0 (healthy loans) is 100%
    - The precision of 1 (unhealthy loans) is 84%
      
The machine learning model was able to predict the precision, or accuracy of positive predictions, for the healthy loans perfectly.  However, the model could not predict the precision of unhealthy loans quite as well.
 
  - Recall
    - The recall of 0 (healthy loans) is 99%
    - The recall of 1 (unhealthy loans) is 94%
      
The machine learning model was able to catch the recall, or percentage of positives cases that were identified correctly, for the healthy loans near perfectly.  The model did quite well identifying the recall percentage for the unhealthy loans.

Machine Learning Model 2:
  - Accuracy
    - According to the confusion matrix the accuracy is 99%

  - Precision
    - The precision of 0 (healthy loans) is 100%
    - The precision of 1 (unhealthy loans) is 84%
      
The machine learning model was able to predict the precision for both the healthy and unhealthy loans perfectly.

  - Recall
    - The recall of 0 (healthy loans) is 99%
    - The recall of 1 (unhealthy loans) is 99%
      
The machine learning model was able to catch the recall for both healthy and unhealthy loans near perfectly.
   

Summary
-
From the results, we can determine that enhancements were made to the machine learning model once we aded resampled data.  I would recommend the resampled data model over the original in order to train the model to accurately identify unhealthy loans.
