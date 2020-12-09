# estimation-auctions-probability
The following notebooks contains the operations of data cleaning, feature engineering, EDA, Model estimation and Hyperparameter Optimization, in the process of calculating the award probability of real estate auctions.
Here are listed some of techniques used:

* Including dummy variables at different levels of a numerical variables to allow for heterogeneous effect of the regressors on the dependent variables
* Visualization techniques on Seaborn focused at comparing different auctions characteristics between awarded and unawarded auctions
* Missing values imputation using Regression
* Bins optimization for the cutoff of a categorical variables using a Decision Tree classifier
* Outlier detection and elimination using Isolation Forest
* Addition Polynomial Features filtered with Principal Component Analysis
* Model Training using Random Forest, Logistic Regression, Naive Bayes and KNN
* Hyperparameter optimization using Cross-Validation
* Stacking to further increase model accuracy
