# Lending Club Loan Analysis and Classification

Lending Club is a peer to peer lending company based in the United States, in which investors provide funds for potential borrowers and investors earn a profit depending on the risk they take (the borrowers credit score). Lending Club provides the "bridge" between investors and borrowers

# Introduction
The Aim for this is project to classify the loan defaulters . The dataset has 396030 rows and  27 columns (lending_club_loan_two.csv).
The data is taken from [kaggle](https://www.kaggle.com/wendykan/lending-club-loan-data)

# Contents
The notebook is divided into 4 section
1. Exploratory Data Analysis  
2. Data Preprocessing: Various preprocessing techinqiues were used to handle
      * Missing data
      * Categorical data
      * Drop unnecessary columns
      * Feature Engineering
3. Training Multi layer neural network (Keras)
4. Evaluating the model Performance

# Results
As the model was imbalanced , accuracy would not be the correct metric for the evaluation , the model was evaluated using Auc socre and F1 score metrics . The model evaluated on test data has f1 score of 70% and auc score of 0.71.

 
