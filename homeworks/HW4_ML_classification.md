# Homework 4: Building and applying a classification model - due 11:59 PM November 2<sup>nd</sup>

For this exercise you will use the ‘wine’ dataset available as a sci-kit learn dataset, and the multi-layer perceptron classifier (MLPClassifier). 

## Part 1 (5 points): Model construction
Following the method that we have discussed in class, build an MLPClassifier model to predict the target variable from the feature data. 

## Part 2 (5 points): Explore hyperparameter space
You will explore the parameter space of the MLPClassifier model and determine the combination(s) of number of layers and number of neurons that yield the best model accuracy score. 

* Produce a figure that illustrates the results of your analysis. Write a short paragraph (at least 2 sentences) explaining your results. If more than one combination of layers/neurons results in a high accuracy score (>0.9), which combination of layers/neurons would you use and why?

* For each combination of layers/neurons that yields an accuracy score > 0.9, calculate the confusion matrix, precision, recall and f1-score for each target class. Describe the implications of your results for model performance for each target class and choose which layers/neurons you will use in the final version of your model.

## Part 3 (5 points): Apply your tuned model
Use the final version of your model, developed using the steps above, to predict the class for the ‘unknown’ samples found in the `unknown_wine.csv` file in the `data` folder on the class GitHub page. 

Find a scikit-learn function that will give the probability that each unknown wine fits into each of one of the three target classes. List the probabilities for each unknown sample for each target class and comment on your results.


## Homework submission:
To submit your homework on Canvas, please upload the link to your github repository containing your HW4 folder, which should have your jupyter notebook saved inside it. 


Your homework will incur a 10% per day late penalty if submitted after the deadline. I will not accept any work submitted after November 9<sup>th</sup>.
