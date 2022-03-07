# BUSA3020 Advanced Analytics Techniques Group Project
# German Loan Prediction
## Executive Summary 
The report employs various predictive algorithms and models to minimize the risk of giving bad loans and refusing good loans. Logistic regression with Reduced Variables using Python’s recursive feature elimination and oversampled bad loans proved to be the most appropriate model with the lowest cost matrix score. Random forest with reduced variables and oversampled bad loans had the highest F1 score overall in 20 Fold cross-validation. However, random forest performed rather poorly for test-on-test data. Given Logistic regression’s superiority to other models in 70:30 Random Sampling and repeat testing hundred times, this report concludes Reduced variable Logistic Regression to be the most appropriate model. A 93% Kaggle Score achieved through this model further supports this conclusion. 

Background and Situational Review
Nature of Problem
Approving a bad loan and refusing a good loan is a risk, one more costly than the other, financial institutions bear every day. This report seeks to create a predictive model to aid loan managers in minimising the financial risk by predicting bad loans efficiently and accepting good loans.

Current Situation 
A German Credit Data set, containing 20 variables (Table 1) and 800 observations, is used to generate a predictive model. The model obtained is employed to predict the credibility of an additional 150 observations containing the same variables, however, without a credibility score.

### Research Question
Can a predictive model minimize the cost of giving bad loans and refusing good loans?

## Data handleing Preperation
Based on the data visualisation of different variables, it is reasonable to combine some categories of variables due to less observation and similar features such as Guarantors and 








