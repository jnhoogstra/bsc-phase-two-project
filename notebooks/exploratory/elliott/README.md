# King County House Sales Predictive Model

**Authors:** Elliott Iturbe, Jacob Hoogstra , Lorin Helfenstein 

## Overview
The goal of this project is to create the best predictive model for the real estate firm in order for then to make business recommendations to clients on the price of their property. Descriptive analyses of data on previously sold houses revealed that our model would take in a number of features.

## Business Problem
A Seattle real estate firm would like to create a tool that allows their clients to enter information about their home and receive a prediction for their home's sale price. To help them in this area, we will create a multilinear regression model to help predict the price of a house based off of the properties features.

## Data
We examined data on square foot living, square foot 15, bathrooms, year built, latitude, condition, view, longitude, month sold, zipcode, waterfront, year sold and grade against price. 

## Methods
Our process started with exploring the data set provided to obtain a stronger understanding of what information we were working with.  After some initial analysis of the data replaced a small handful of null values, dropped the id column, and changed the datatypes for some of the columns in the data set.

This visualization shows the three most correlated values to price.

![graph1](./images/3mostcorr.png)

This is a visual illistrates the correlation between the price of the house and the date sold.

![graph2](./images/priceofhomebydate.png)

During development we used a basic baseline model which yeilded a R-squared value of 0.537 and a root mean squared error of 176247.623, as a starting point with the most correlated values shown above, and used this model to compare future iterations to. From there we engineered some new features and removed major outliers and continued to work on developing the model. 

## Results
After a good amount of trial and error, and applying various techniques including log transforming our target, scaling our data, and finally using polynomial features we arrived at our final advanced model which yeilded a R-squared value of 0.796 and a root mean squared error of 0.218 which had been log transformed.

# Next Steps
Features we would like to add but ran out of time to produce include using lat and long and zipcode to produce more advanced features like distance to nearest beach or body of water, and neighborhood statistics. Another thing we could look at to improve the model is to log transform other features to make more normal distributions, however, many of our features are categorical values. As well as started to look at creating a price map of the county, but again ran out of time to produce the visual.

## Conclusions
After many models and tries we created a final model. The model created has a R-squared value of 0.796 paired with a root mean squared error of 0.218. Our analysis focuses on specific features, compared to price we understand that their our other features that could be used not given in out data set..


## For More Information
Please review our full analysis in [our Jupyter Notebook](./report.ipynb) or our [presentation](./microsoftmovieanalysispowerpoint.pdf).

For any additional questions, please contact **Elliott Iturbe at eaiturbe@bsc.edu, Jacob Hoogstra at jnhoogstra@crimson.ua.edu, or Lorin Helfenstein at lehelfen@bsc.edu**

## Repository Structure

```
├── data                                  <- data files used for analyses
├── images                                <- visualizations created
├── notebooks                             <- code written for project with explanation, as well as working notebooks of members
├── microsoftmovieanalysispowerpoint.pdf  <- PDF version of powerpoint
└── README.md                             <- overview of project
```
