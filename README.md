# Systems Biology Insights into the Molecular Genetic Basis of Blood Pressure
Developing a machine learning method for blood pressure gene prioritisation.

Notebooks containing codes and code output:

1. Labelling Training Data Categories: building the training dataset by setting the conditions of each class.

2. Keras optimising: building and altering deep neural network build for an optimised model for the BP data.

3. BP Causal Gene Prediciton (benchmarking and feature importance included): the core code producing prioritised genes to enter pathway and systems analysis. Includes: data preprocessing, comparing models accuracies, and comparing their important features before using top performing model for gene prioritisation.


4. Calculating knockoffs_for_feature_importance.html: R markdown showing code to apply knockoff statistical analysis and output. Aims to identify statisitcally significant features the models should be using.

5. Plotting Nested-CV Accuracies.html: R markdown producing presentable plot of nested-CV accuracies for each model produced in file 2.

6. Plotting F1scores.html: R markdown producing presentable plot of F1 scores for each model produced in file 2.

7. Ordering prioritised gene loci.html: Using gene prirotisation predictions and loci information to view loci prioritisations.

