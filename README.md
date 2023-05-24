# Machine-learning-dabases-Iris-dataset
This is a Machine Learning project in data science. The Taxonomy of the Iris flower.

A machine learning project may not be linear, but it has several well-known steps:

Define problem.
Prepare data.
Evaluate algorithms.
Improve the results.
Show results.

Here’s an overview of what we’ll cover:

We will use Google Colab.
Loading the data set.
Summarizing the data set.
Visualizing the data set.
Evaluating a few algorithms.
Making a few predictions.

Vamos avaliar 6 algoritmos diferentes:

Regressão Logística (LR)
Análise Linear Discriminante (LDA)
K-vizinhos mais próximos (KNN).
Árvores de Classificação (Decision Tree) e Regressão (CART).
Gaussian Naive Bayes (NB).
Support Vector Machines (SVM).

This is a good mix of simple linear algorithms (LR and LDA), nonlinear (KNN, CART, NB and SVM). We reset the random numeric seed before each execution to ensure that the evaluation of each algorithm is performed using exactly the same data divisions. This ensures that the results are directly comparable.

Now we have 6 models and precision estimates for each. We need to compare the models to each other and select the most accurate ones.

Note that your results may be different. For more information, see the post:

[Embrace Randomness in Machine Learning](https://machinelearningmastery.com/randomness-in-machine-learning/)

In this case, we can see that it seems that Support Vector Machines (SVM) has the highest estimated Accuracy score.

We can see that Accuracy is 0.9 or 90%. The confusion matrix provides an indication of the three mistakes made. Finally, the rating report provides a breakdown of each class by accuracy, recall, score-F1 and support showing excellent results (given that the validation dataset was small).

You can learn more about making predictions and predicting probabilities here:

[How to make predictions with scikit-Learn](https://scikit-learn.org/stable/modules/cross_validation.html)
