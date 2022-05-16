# Neural_Network_Charity_Analysis
Deep Learning module
## Overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis was to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. We received the dataset from Alphabet Soup’s business team, which contained more than 34,000 organizations that have received funding from Alphabet Soup over the years. We used the TensorFlow platfrom to classify the success of charitable donations. 


## Results: Using bulleted lists and images to support your answers, address the following questions.

![image](https://user-images.githubusercontent.com/96274446/168504141-63b5e735-a05d-458d-9b0a-6ca8a68799a9.png)
![image](https://user-images.githubusercontent.com/96274446/168504171-4201b01f-0130-4214-b2d7-8a40ced69638.png)
![image](https://user-images.githubusercontent.com/96274446/168504196-164283c2-35f3-44ed-9767-ff9211da68d9.png)
![image](https://user-images.githubusercontent.com/96274446/168504218-5f1fb154-4857-40d8-bb6e-9387a466e0f2.png)


## Data Preprocessing
- The columns EIN and NAME are identification information and have been removed from the input data.
- Columns: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features for the model.
- We encoded the categorical variables, split them into training and testing datasets

## Summary: 
The deep learning module did not reach the 75% as wanted. The highest it could go was 72%. With this, the module is not outperforming. To make sure we get the desired results, we could use a supervised machine learning model like the Random Forest Classifier. This will help us evaulate it against our depp learning model. 
