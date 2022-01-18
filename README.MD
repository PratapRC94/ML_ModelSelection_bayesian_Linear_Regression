****************************************** Linear Regression Model Selection & Implementation Report - README file ******************************************

**Datasets: csv files**

There are currently 4 different categories of data. Each having training features, training labels, testing feature and testing labels.

These datasets are -

* crime .csv
* wine.csv
* artlarge.csv
* artsmall.csv

All the train and test feature datasets contain number of feature values in each line.

**Data Format:**

feature dataset ::

-0.37509	0.95613	   -0.23422		.	.	-0.68813 . . . . .
-0.29631	-0.02099	-0.70877	.	.	-0.68813 . . . . .
	.			.			.		.	.	.
	.			.			.		.	.	.
-0.45387	-0.8149	   -0.62968		.	.	0.029903 . . . . .

label dataset ::

-0.2059
-0.33463
	.
	.
-0.635
	.
	.


**Code Execution Process :** 

* The entire solution is developed in jupyter notebook.
* The ipynb file is kept in a directory and there is a sub-directory called 'pp2data' which contains all the input data files.
* The jupyter notebook contains multiple functions defined to read data files, calculate regularized parameter, Model selection using cross validation, Model selection using Bayesian Linear Regression which are asked in Task -1/2/3.
* The complete program is written in a single cell with main() function at the end and other user defined functions above. The main() function takes the input selection from user as it prompts to give a data set selection option.
* All the csv input files automatically get detected in the 'pp2data' directory and asks the user to chose which dataset to execute through the prompt.

**Input :**

* Enter 1 for wine
* Enter 2 for artlarge
* Enter 3 for crime
* Enter 4 for artsmall

The user selects either of 1/2/3/4 as per their choice of data set and the program proceeds with the selected train, test of feature and labels data set to read it from the directory 'pp2data' and process for the given tasks.

** Output:**

For Task 1 - Regularization

	* Minimum MSE of complete test data
	* Lambdaa for Minimum MSE of complete test data 
	* Execution/Run time for Task 1 - Regularization 
	* Plot of training and testing MSE against range of Lambdaas

For Task 2 - Model Selection using Cross Validation

	* Minimum MSE of k-fold cross validation data
	* Lambdaa for Minimum MSE of k-fold cross validation data
	* MSE of test data for best chosen lambdaa
	* Execution time for Task 2 - Model Selection using Cross Validation 
	* Plot of testing MSE for best Lambdaa chosen fron CV
	* Comparison Plot of Training - Testing - Cross Validation testing MSE

For Task 3 - Bayesian Model Selection

	* Initialized and Finalized Alpha parameter
	* Initialized and Finalized Beta parameter 
	* Effective Lambdaa for Bayesian Hyper-parameters
	* MSE of test data set for Bayesian lambdaa
	* Execution time for Task 3 : Bayesian Model Selectio 
	* Comparison Plot of Training - Testing - Bayesian LR testing MSE
