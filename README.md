# ccfmodel1
This is my capstone project
In this machine learning and Python project, here we solve the problem of detecting credit card fraud transactions using machine numpy, scikit learn, and few other python libraries. here i am trying to overcome the problem by creating a binary classifier and experimenting with various machine learning techniques to see which fits better.
approach to building the classifier is discussed in the steps:
1.	Perform Exploratory Data Analysis (EDA) on our dataset
2.	Apply different Machine Learning algorithms to our dataset
3.	Train and Evaluate our models on the dataset and pick the best one.
Step 1. Perform Exploratory Data Analysis (EDA)
check for null values in the credit card dataset
check the number of occurrences of each class label and plot the information using matplotlib
•	Let’s plot the above information using matplotlib.
it’s time to split credit card data with a split of 70-30 using train_test_split().
**Step 2: Apply Machine Learning Algorithms to Credit Card Dataset
This is actually a binary classification problem as we have to predict only 1 of the 2 class labels. Apply a variety of algorithms for this problem like Random Forest, Decision Tree, Support Vector Machine algorithms, etc.
In this machine learning project, we build Random Forest and Decision Tree classifiers and see which one works best. Address the “class imbalance” problem by picking the best-performed model.
The Decision Tree algorithm is a supervised machine learning algorithm used for classification and regression tasks. The algorithm’s aim is to build a training model that predicts the value of a target class variable by learning simple if-then-else decision rules inferred from the training data.
Let’s build the Random Forest and Decision Tree Classifiers. They are present in the sklearn package in the form of RandomForestClassifier() and DecisionTreeClassifier() respectively.
Step 3: Train and Evaluate our Models on the Dataset
The Random Forest classifier has slightly an edge over the Decision Tree classifier.
•	Let’s create a function to print the metrics: accuracy, precision, recall, and f1-score.
•	Let’s visualize the confusion matrix and the evaluation metrics of our Decision Tree model.
Evaluation of Decision tree Model
•	Let’s visualize the confusion matrix and the evaluation metrics of our Random Forest model.
 
Address the Class-Imbalance issue
Let’s visualize the predictions of our model and plot the confusion matrix.
Evaluation of Random Forest Model
