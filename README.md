# Binary Classification with Sci-kit Learn

### **Problem Statement**
Mobile carrier Megaline has discovered that many of its subscribers use legacy plans. They want a model that will analyze subscribers' behavior and recommend one of Megaline's newer plans, Smart or Ultra, with a minimum accuracy score of 75%. For this binary classification task I aim to develop a model with the highest possible accuracy. I will employ three classification algorithms to train the model. The trained model with the highest accuracy score will be delivered to Megaline. The three learning algorithms I will employ are:

1. Decision Tree Classifier
2. Random Forest Classifier
3. Logistic Regression Classifier

The data Megaline has provided represents the behavior of users who have already switch to one of the new plans from the legacy plans. The data was pre-processed in a previous analysis I did for Megaline. Every observation in the dataset contains monthly behavior information about one user. The information given is as follows: 

- сalls — number of calls
- minutes — total call duration in minutes
- messages — number of text messages
- mb_used — Internet traffic used in MB
- is_ultra — plan for the current month (Ultra - 1, Smart - 0)

I will use the accuracy score function provided by the sklearn metrics library to evaluate the trained models
