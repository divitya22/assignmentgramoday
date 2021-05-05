# assignmentgramoday
Gramoday Data Science assignment
# Predict prices in Agra for potato:

1.What are the data pre-processing/cleaning technique you would apply?

	There are several methods to preprocess and clean the data before we build our predicted model. Firstly, we will try to understand the features /variables we have got in the data set. we will start with visual exploration since the number of features are less in current data and we can do it manually by comparing month from price data feature with another features.

	Identifying and encoding the categorical features: In this step we will check the categorical features and convert them into numbers since we plan to use Linear Regression model. It requires all features in numeric form. For eg. feature Market Name we can convert in to numeric by labeling it like Anchor as 1, Fatehabad as 2 and similarly for other categorical features.

	Using Boxplot, we can identify outliers in our data. 

	Then we must deal with missing values. We will identify missing or Na values. If entire row or entire column has missing values then it’s better to remove them or else we can try to replace missing value by mean, mode and median.

	Feature scaling: This step is important when we have values scale different than normal because it can cause more outliers. 

	Feature Selection: We will need to identify column which are important for the model in this step.
For eg: Grade column does not seem to be useful for our model so we can drop this column.

     
2) What are the features you would use to create model?

	District Name	Market Name	Commodity	Variety Min Price	Max Price	Modal Price Price Date


3) How would you frame this problem as machine learning problem? What would be the target variable?
   
	Modal price will be the target/dependent variable.


4)Which algorithm would you prefer for price prediction?

	Linear Regression or Random Forest Regression


5)What would be the loss function you would use?

	Mean Square Error will be the loss function in our regression model. We will use stochastic     gradient descent to minimize the value of loss function.
