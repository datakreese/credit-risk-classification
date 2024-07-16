# Credit Risk Analysis Report

# Overview
This machine learning model seeks to predict the health of a small loan by considering 8 different credit factors. It is designed with numpy, pandas, and sklearn libraries.  The data is divided into training and testing sections, then fed through a logistic regression algorythm. Finally, a confusion matrix and classification report are printed in the final five cells for review.

# Results
- Accuracy: Appears to be 99.18% for the overall model. 
- Precision: Healthy Loans can be predicted at 100% while high-risk loans were predicted correctly at 85%.
- Recall: Once again we see different results for each category. The healthy loans were identified 99% of the time while high-risk loans were correctly categorized 91% of the time.

# Summary 
All loans in this dataset are under $15,000 which is relatively small for a bank or credit union. However, the number of customers (77,000+) and scale of potential mistakes need to be explored before deploying the current model. 

 The confusion matrix suggests this is an overly cautious model. Roughly 15% of loans labeled high-risk were actually healthy. This would likely drive away customers with lower credit scores whose credentials cluster right on the edge of the two categories. Ensuring the weaknesses of this model align with company growth goals would be important before implementing this model.
