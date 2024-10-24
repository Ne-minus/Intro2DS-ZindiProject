# Intro2DS-ZindiProject

## Task Description  
Problem: Predict if a user will be active on Zindi next month by their participation in competitions, submissions, or forums.
Importance: Helps Zindi enhance user engagement, optimize services, and increase platform efficiency.
ML Contribution: Analyzes user behavior to predict future activity, reducing costs and improving user experience.

## About data

The dataset consists of multiple files detailing hackathons and competitions, user participation, submissions, discussions, and comments, along with metadata explaining each variable. The train and test sets are summarized views of user activity, with the test set requiring predictions for specific users based on month and year, following the format shown in the Sample Submission.

### Main data features and problems
**Class disbalance**
The "0" class is significantly larger than the "1" class, which can lead to overfitting, challenges in evaluation (since standard accuracy metrics are unsuitable), and longer training times.
**Outliers**
Outliers in the data can increase error rates by affecting the loss function, distort statistics like the mean and standard deviation, and lead to overfitting by capturing noise instead of true patterns. Additionally, the data contains many categorical features and unnecessary information, further complicating analysis.
**Correlations**
Some features show a high correlation with each other, and the target variable is fairly highly correlated with certain features. This suggests potential multicollinearity and key relationships between the target and specific predictors.
