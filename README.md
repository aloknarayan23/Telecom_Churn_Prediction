# Telecom Churn Prediction
In the telecommunication industry, customers tend to change operators if not provided with attractive schemes and offers.
It is very important for any telecom operator to prevent the present customers from churning to other operators.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)

## General Information
- Problem:
		In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another.
		In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate.
		Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.
		For many incumbent operators, retaining high profitable customers is the number one business goal.
		To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. 
		
		
- Agenda :
		The main goal of the case study is to build ML models to predict churn. The predictive model that you’re going to build will the following purposes:
			1. It will be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc.
			2. It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks.
			3. Even though overall accuracy will be your primary evaluation metric, you should also mention other metrics like precision, recall, etc. for the different models that can be used for evaluation purposes based on different business objectives. For example, in this problem statement, one business goal can be to build an ML model that identifies customers who'll definitely churn with more accuracy as compared to the ones who'll not churn. Make sure you mention which metric can be used in such scenarios.
			4. Recommend strategies to manage customer churn based on your observations.	
	
- DataSet : 
		day.csv

- Steps Followed : 
		1. Exploring Data
		2. Data Cleaning
		3. EDA
		4. Data Modeling and Model Evaluation
		5. Feature Selection
		6. Prediction on Test Data


## Technologies Used
Language : Python 

Libraries : 
      - pandas (To work with dataset)
      - numpy (Math library)
      - seaborn (Graph library that use matplot in background)
      - matplotlib.pyplot (to plot some parameters in seaborn)
      - warnings (to ignore warnings)
	  - sklearn.model_selection (to split the dataframe into Train and Test)
	  - sklearn.preprocessing (Using StandardScaler to Rescaling the features)
	  - sklearn.feature_selection (Importing RFE)
	  - sklearn.linear_model (Importing LinearRegression)
	  - statsmodels.stats.outliers_influence (Check for the VIF values of the feature variables)
	  - statsmodels.api (Building linear regression model)
	  - sklearn.metrics (R-squared score)
	  - sklearn.model_selection (KFold, GridSearchCV,StratifiedKFold)
	  - sklearn.decomposition (PCA)
	  - sklearn.svm (SVC)
	  - sklearn.ensemble (RandomForestClassifier)
	  - sklearn.neighbors (NearestNeighbors)
	  - sklearn.tree (DecisionTreeClassifier)
	  - six
	  - IPython.display
	  - sklearn.cluster
	  - random

## Contact
Created by :
        Alok Narayan(https://github.com/aloknarayan23)
		            - feel free to contact me!