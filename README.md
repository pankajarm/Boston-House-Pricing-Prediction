# Boston-House-Pricing-Prediction

In this nano project, We'll use Multiple linear regression (many Variables) to make prediction of Boston House Pricing from
the given set of variables like number of rooms, square feet size of house, etc.

We are using SciKit Learn to Create Linear Regression Model

Read more about SciKit Learn LinearRegression Here http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html

In this model we are using Multiple Linear Regression equation 
y = m1x1+ m2x2 + m3x3 +.....mnxn +b

In our example (These are given from data):

y is  MEDV: Median value of owner-occupied homes in $1000's

x1. CRIM: per capita crime rate by town 

x2. ZN: proportion of residential land zoned for lots over 25,000 sq.ft. 

x3. INDUS: proportion of non-retail business acres per town 

x4. CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise) 

x5. NOX: nitric oxides concentration (parts per 10 million) 

x6. RM: average number of rooms per dwelling 

x7. AGE: proportion of owner-occupied units built prior to 1940 

x8. DIS: weighted distances to five Boston employment centres 

x9. RAD: index of accessibility to radial highways 

x10. TAX: full-value property-tax rate per $10,000 

x11. PTRATIO: pupil-teacher ratio by town 

x12. B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town 

x13. LSTAT: % lower status of the population 

These will be generated during model fit process

m1 is the slope (relationship factor ) between x1 and y, m2 is the slope between x2 and y, m3 is the slope between x3 and y, so on

b is constant value 


Long Story short, They way it works (atleast in my understanding..), is SciKit Learn LinearRegression model will try to create a model of equation type y = mX + b from the given data which has BMI (X) and Life Expectancy (y), via fitting all values of x1 in relationship to y by finding slope m and by adding b (a constant value) to it.
same goest to other variables x2, x3, ..., x13

Basically, by using SciKit Learn Linear Regression fit method, we are telling it to find correct relationhip for example, between given Data of x1 (CRIME in the Area) and y (Median House Value)

Hope it all make sense to you...

Read more about varibles relationship to house pricing here.

https://archive.ics.uci.edu/ml/datasets/Housing
