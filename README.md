# INSTRUCTIONS

- In order to not have everything in a single file, take **preprocessing** file as a template.

- If you want to improve the preprocessing part, just create a new version of the preprocessing file.

- If you want to train a model, just create a new file from the template and rename the file with the name of the model. If you want to improve a model, just rename it with the name of the model and v{number of version}

# Results so far

We trained the data with 6 different models:

- Logistic Regression.
- Linear Discriminant Analysis.
- Quadratic Discriminant Analysis.
- Regularized Discriminant Analysis.
- Naive Bayes Classifier (with Bernoulli distribution).
- Perceptron.

In each file *{model}.ipynb*, you can find all the hyperparameter tunning and different experiments, and in *all_models.ipynb* you can find the comparison between all models with their best parameters.

Finally, the best model is LDA, with a F1-Score of 0.62.