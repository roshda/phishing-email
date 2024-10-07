# Phishing Email Classifier

## Overview
I built this project to classify phishing emails based on the text of the email using machine learning. I trained a logistic regression model.

## Dataset
- The training dataset contains 8,348 labeled examples
- The test dataset contains 1,000 unlabeled examples
  
### Data Format:
Each email has the following columns:
- id
- subject line
- email (body text).
- values (a label where 1 is a phishing email and 0 is a legitimate email)

## Project Components

1. EDA, Feature Engineering
   - Extract features from email text, visualize.
   
2. Modeling
   - Apply logistic regression for classification.
   - Use cross-validation to evaluate model performance and prevent overfitting.
   
3. Evaluation
   - acuraccy, precision, recall, F-1 score.
   
4. Test on unlabeled data


## Credits

The dataset is from a Data Science class at UC Berkeley.
