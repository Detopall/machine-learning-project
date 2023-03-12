# Machine learning project

## Table of Contents

- [Notebooks](#notebooks)
  - [Outcome Profit](#outcome-profit)
  - [Outcome Damage Inc](#outcome-damage-inc)
  - [Outcome Damage Amount](#outcome-damage-amount)
  - [Best 200 Smurfs](#best-200-smurfs)
- [Excel Files](#excel-files)
  - [Train V2](#train-v2)
  - [Score](#score)
  - [Train V2 Cleaned](#train-v2-cleaned)
  - [Score Cleaned](#score-cleaned)
  - [Top Customers](#top-customers)

## Notebooks

---

In this section the notebooks, where all the code is written, are explained. These notebooks contain most of the models and technics used during the lessons.

### **Outcome Profit**

Outcome profit tries to predict the feature 'outcome_profit'. We've used 'PolynomialRegressor', 'KNN', 'DecisionTree', 'RandomForestRegression' and 'GradientBoostingRegressor'.

The best model is RandomForestRegression with a training score of 84.7% and a validation score of 79.5%. This model was used on the score file to predict the 'outcome_profit' feature.

### **Outcome Damage Inc**

This file is used to classify the smurfs between the class 'will cause damage' and 'will not cause damage' (1 and 0). We used models such as 'Logistic Regression', 'Polynomials' combined with 'Penalisation', 'KNN Classification', 'GradientBoostingClassifier' and 'Support Vector Machines'.

Skipping to the evaluation, the best model, 'Logistic Regression' was used.

### **Outcome Damage Amount**

Outcome damage amount used the same functionality as the 'outcome_profit' file. This is because both need to predict a numerical value that is not bound to a class (such as with 'outcome_damage_inc').

This feature caused some problems for the training and testing of the models. Looking at the evaluation the best validation score is 6.0% with a training score of 20.7%.

RandomForestRegressor was the model used to predict the 'outcome_damage_amount' feature.

### **Best 200 Smurfs**

We needed to pick out the best 200 smurfs. This has been done by using code and determining based on the values of features what the best 200 people were.

In the report the reason behind these 200 smurfs has been elaborated on.

## Excel Files

---

Some files were given as part of the training and testing of the models. Others we needed to use in order to display information.

### **Train V2**

This excel file was given by our lecturer and used for data cleaning purposes. After cleaning this data this file was transformed into the file named: 'train_V2_cleaned'.

### **Score**

'score.csv' was also given by our lecturer and needed to be used as unseen data. This file had to undergo the same data cleaning as 'train_V2' and was also transformed in another file called 'score_cleaned'.

### **Train V2 Cleaned**

After the file 'train_V2' has been cleaned, this file was used to train the models.

### **Score Cleaned**

After the file 'score' has been cleaned, this file was used to predict the values from the best models.

### **Top Customers**

'top_customers' contains 200 smurfs with the best data possible. In the report the ideal smurfs is also described based on these findings.
