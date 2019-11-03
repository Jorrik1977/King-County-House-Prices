# King-County-House-Prices

This project iterates the Data Science Lifecycle over the well known King County House Prices dataset. Here you find a description of the chapters and my working procedure in my Jupyter Notebook File. Our task is described in the instructions.

**Meaning of the features** 

Some of the features were not clear in meaning. You will find the research for bathrooms, grade and condition in that part

**Analyze the dataset** 

**Cleaning the dataset** 

**Missing values** 

Mistyped number of bedrooms, "?" in sqft_basement, missing values in waterfront, view and 

**Duplicates?** 
No

**EDA** 

* Analyze the target "price" in depth

* Normalize y

* Visualize y versus lat + longitude

* Median price per zipcode, most expensive zipcodes  98039, 98004, 98040, 98112, 98005

* Median price waterfront vs. normal distribution

* Price per month 2014-15

**Features vs. Price / Correlation** 

Correlation matrix

**Outstanding Features** 

* Numeric: Sqft_living, sqft_above, sqft_living15, grade

* Drop sqft_above (multicolinearity)

**Categorical Features** 

Categorical: grade, waterfront, view, zipcode, latitude

**Multicolinearity/Dummy variables** 

**Normalisation of Features** 

**Prediction**

* Split target and features

* Split train and test data

* Train the model and then test it

**Multilinear Regression** 

* Create dummy variables, drop first value automatically

* Calculate R-squared/ adj. R-squared


