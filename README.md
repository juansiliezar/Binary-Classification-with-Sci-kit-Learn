# Binary Classification with Sci-kit Learn: Megaline Plan Recommendation

## Problem Statement
Mobile carrier Megaline has identified a challenge with a substantial number of their subscribers sticking to outdated service plans. The objective is to develop a predictive model that analyses subscriber behavior and accurately recommends one of the newer, more advantageous plans—either Smart or Ultra. The target is to achieve a minimum accuracy of 75%, aiming for the highest possible accuracy to ensure effective plan recommendations.

## Solution Approach
This project utilizes three different machine learning algorithms for the binary classification task:
- **Decision Tree Classifier**: A model that uses a tree-like graph of decisions and their possible consequences.
- **Random Forest Classifier**: An ensemble learning method for classification that constructs a multitude of decision trees at training time.
- **Logistic Regression Classifier**: A statistical model that in its basic form uses a logistic function to model a binary dependent variable.

## Data Description
The dataset provided by Megaline includes behavior metrics of users who have already transitioned from legacy to newer plans. Each record in the dataset represents monthly behavior data of a single user with the following attributes:
- `calls`: Number of calls made by the user.
- `minutes`: Total duration of calls in minutes.
- `messages`: Number of text messages sent.
- `mb_used`: Data usage in megabytes.
- `is_ultra`: Current plan of the user (1 for Ultra, 0 for Smart).

## Model Evaluation
Models will be evaluated based on their accuracy using the `accuracy_score` function from the `sklearn.metrics` library. The model with the highest accuracy will be recommended for implementation to assist Megaline in promoting their newer plans effectively.

## Conclusion
The final deliverable will be the model that best categorizes subscribers into the most suitable plan, fostering better customer satisfaction and enhanced service usage.
