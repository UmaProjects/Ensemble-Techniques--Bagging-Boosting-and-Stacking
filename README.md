# ensemble methods
 ensemble(combination) of various models into one effective model
The three main terms in ensemble techniques are
 1) Bagging--> decrease the variance
 2) Boosting-->decrease the bias
 3) Stacking--> increase the predictive force of the classifier

The principle behind ensemble modelling is to group weak models together to form one strong model.

# Concept behind Bagging:
	Samples are bootstrapped each time when a model is trained.
	Samples are choosen randomly from the training set and they are used to validate the predictions and then the samples are replaced back in the training set(with replacement).

# Concept behind Boosting:
	The concept revolves around correcting the previous classifier mistakes.
	Each classifier gets trained on the sample set and learns to predict.The misclassification errors are then fed into the next classifier in the chain and are used to correct the mistakes until the final model predicts accurate results.

# Concept behind Stacking:
	A new model is trained from the combined predictions of two (or more) previous model.
	The predictions from the models are used as inputs for each sequential layer, and combined to form a new set of predictions.
	
	



Here I am using a housing dataset from pydataset and convert them into evenly spaced bins and classify them using all the above ensemble terms and evaluating the performance of each term.







