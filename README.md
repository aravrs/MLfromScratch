# Machine Learning from Scratch [[nbviewer]](https://nbviewer.jupyter.org/github/AravRS/MLfromScratch/tree/master/)


Implementation of some Machine Learning Algorithms from Scratch, using only Math, coded in *Python*.

  * [Regression](#regression-from-scratch)
  * [Classification](#classification)
    + [Logistic Regression from Scratch](#logistic-regression-from-scratch)
    + [Decision Trees from Scratch](#decision-trees-from-scratch)
  * [Clustering](#clustering)
    + [K-Means from Scratch](#k-means-from-scratch)
    + [Expectation-Maximization Gaussian Mixture from Scratch](#expectation-maximization-gaussian-mixture-from-scratch)


## Regression from Scratch

* Necessary Imports
* Loading & Pre-Processing Data
* Simple Regression Model *(closed form solution)*
	* Fitting the simple regression
	* Predicting Values
	* Residual Sum of Squares *(RSS)*
	* Inverse Predictions
* Multiple Regression Model *(gradient decent)*
	* Gradient Descent
	* Fitting  Multiple Regression
* Ridge Regression 
	* L2 regularization
	* Fitting Ridge Regression
* Normalization
* Lasso Regression 
	* L1 regularization
	* Fitting Lasso Regression
	* Fitting  Lasso Regression with more features
* K-Nearest Neighbors Regression
	* 1-nearest neighbor regression
	* k-nearest neighbor regression
		* Choosing the best value of k using a validation set

## Classification

### Logistic Regression from Scratch

* Necessary Imports
* Loading & Pre-Processing Data
	* Remove punctuation
	* Compute word counts (only for important_words)
* Logistic Regression Model
	* Predict Probability
	* Compute (log-)likelihood
	* Gradient Ascent
	* Fitting the Model
		* Making predictions
		* Evaluating the Model
* Logistic Regression with L2 Regularization
	* L2 penalty
		* Compute (log-)likelihood with L2 penality
		* Gradient Ascent with L2 penality
	* Fitting the Model
		* Measuring Accuracy 

### Decision Trees from Scratch

* Necessary Imports
* Loading & Pre-Processing Data
* Decision Tree Model
	* Building the Tree
	* Fit the Tree
		* Making predictions
		* Evaluating the Model
* Overfitting
	* Fitting the Tree
		* Evaluating the model
* Complexity of the Tree
* Fitting Many Different Models
* Weighted Decision Trees
	* Boosting a Decision Stump
	* Training a Boosted Ensemble of 10 Stumps
		* Making Predictions
		* Performance Plots

## Clustering

### K-Means from Scratch

* Loading & Pre-Processing Data
	* Loading tf-idf
* K-Means Model
	* Assigning clusters
	* Revising clusters
	* Assessing convergence
* Combining into a single function
* Plotting Convergence Metric
* Local Maxima
* K-Means++ Model
* Assessing K-Means and K-Means++
* Choosing k value
* Visualizing clusters of documents

### Expectation-Maximization Gaussian Mixture from Scratch

* Loading & Pre-Processing Data
* Log-Likelihood
* Expectation-Maximization Model
	* Different Clusters
