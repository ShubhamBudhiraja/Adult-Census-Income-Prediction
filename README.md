# Adult Census Income Prediction
This project focuses on predicting whether the annual income of an individual is more or less than $50,000. And to accomplish this task, the project was divided into four different sections:
1. Dataset Visualisation
2. Data Preprocessing
3. Training the Dataset
4. Observations & Conclusions

# Dataset Visualisation
The dataset "Adult Census Income" from the UCI Machine Learning Repository was used in this project. The dataset was extracted from the 1994 and 1995 Current Population Surveys conducted by the U.S. Census Bureau. It contains 48,842 entries to be exact with 14 attributes:
 1. Age
 2. Workclass  
 3. Fnlwgt 
 4. Education
 5. Education-num
 6. Marital-status
 7. Occupation
 8. Relationship
 9. Race
10. Sex
11. Capital-gain 
12. Capital-loss
13. Hours-per-week
14. Native-country

At first, it was checked for missing values. Then the categorical and numerical features were separated and graphs are plotted based on different parameters. Once the plotting and analysis of graphs was done, the work was shifted to the next step i.e., Data Preprocessing.

# Data Preprocessing
This section dealt majorly with feature selection and eliminating inappropriate entries which might be irrelevant for the training of the dataset. Taking nto account, the analysis from the previous section, it was clearly observant that the features, "Relationship" and "Eductaion-num" would create nothing but redundancy. So they were dropped. However, there were some entries too that had some uniquely variant values. So they were removed too.

# Training The Dataset
In this step, the dataset was trained on 9 different classification algorithms to identify the best suited one for most accurate predictions. They are:
1. Logistic Regression
2. Decision Tree
3. K-Nearest Neighbours (KNN)
4. Support Vector Machine (SVC)
5. Random Forest
6. AdaBoost
7. Bagging
8. Extra Trees
9. Naive Bayes

The above models were used to predict the test samples and their accuracy scores were noted.

# Observations & Conclusions
All the above models were evaluated and it was found out that AdaBoost and Logistic Regression had accuracy scores of 83.5% which was remarkably good.
