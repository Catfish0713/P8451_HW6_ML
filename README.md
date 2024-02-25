# P8451_HW6_ML

Comparison between Classification Trees, SVM and Logistic Regression

The posted article by Yu et al utilized NHANES data from 1999-2004 to predict diabetes and pre-diabetes using Support Vector Machines. You will conduct a similar analysis using data within the NHANES package in R. For this exercise, you will try to predict Diabetes using similar (although not all) variables. The available data is also  different, so you won't get the same answers.

REMINDER: Look at the frequency of your outcome variable to check for balance

For this assignment, you will:

1. Load the NHANES data using the NHANES R package

2. Restrict the NHANES data to the list of 11 variables below. Perform light data cleaning. Determine if you want to exclude any of the features before you start. Partition the data into training and testing using a 70/30 split.

"Age", "Race1", "Education", "HHIncome", "Weight", "Height", "Pulse", "Diabetes", "BMI", "PhysActive", "Smoke100"

3. Construct three prediction models to predict diabetes using the features from NHANES. You will optimize each model using cross-validation to choose hyperparameters in the training data and then compare performance across models. You will use the following three algorithms to create your prediction models:

a) Classification Tree

b) Support Vector Classifier (i.e. Support Vector Machine with a linear classifier)

c) Logistic regression.

4. Select an "optimal" model and calculate final evaluation metrics in the test set. ONLY ONE MODEL SHOULD BE APPLIED IN THE TEST SET. What do you conclude about your final model's performance?

5. In this analysis, we've used Race as one of the predictors in the model. Briefly discuss the ethical considerations of including race in a disease prediction model. (no more than 1-2 paragraphs)