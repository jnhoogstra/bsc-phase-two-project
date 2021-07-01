# King County House Sales Predictive Model

**Authors:** Elliott Iturbe, Jacob Hoogstra , Lorin Helfenstein 

## Overview
The goal of this project is to create the best multilinear regression model for the real estate firm in order for then to make business recommendations to clients on the price of their property. Descriptive analyses of data on previously sold houses revealed that our model would take in a number of features.
## Business Problem
A Seattle real estate firm would like to create a tool that allows their clients to enter information about their home and receive a prediction for their home's sale price. To help them in this area, we will create a multilinear regression model to help predict the price of a house based off of the properties features.

## Data
We examined data on square foot living, square foot 15, bathrooms, year built, latitude, condition, view, longitude, month sold, zipcode, waterfront, year sold and grade quad against price. 

## Methods
Our process started with organizing our data by dropping irrelevant columns, creating new ones, sorting by specific values, changed the columns to objects, removing major outliers. While working with our data, we used a baseline model to create a helpful starting point. Based off that baseline model we create several other models until we created a final model that yielded the best R squared and root mean squared error.

## Results

This visualization shows which genre of movie Microsoft should make based on which genre has the highest worldwide gross.

![graph1](./images/grouped_barplot_Seaborn_barplot_Python_corrected.png)

This is a visual of how Rotten Tomatoes user-generated ratings vary according to different MPAA ratings of adventure movies.

![graph2](./images/Rotten_tomatose_Ratings.png)

This graph shows the most profitable directors for adventure movies. We conclude that Jean Negulesco is by far the best choice.

![graph3](./images/Directors_and_Profit_for_Adventure_Movies.png)

Buena Vistas Studios ("BV") is responsible 65% of the top 20 grossing movies. If Microsoft is interested in using another studio to make their film, they should contact Buena Vistas.

![graph4](./images/top20_barplot_Seaborn_barplot_Python.png)

This is a comparison of runtime to revenue that reveals there is no true monetary value for creating a movie with a runtime outside of the shaded area.

![graph5](./images/Runtime_Comparison_line_added.png)

This graph shows the average rating of movies according to month of release. Because there is no significant difference between each month, we conclude release month doesn't really matter.

![graph6](./images/Month_and_Rating.png)

## Conclusions
After many models and tries we created a final model. The model created has a R-squared value of 0.7797402432462915 paired with a root mean squared error of 0.216636956049333. Our analysis focuses on specific features, compared to price we understand that their our other features that could be used not given in out data set..


## For More Information
Please review our full analysis in [our Jupyter Notebook](./Final/Notebook.ipynb) or our [presentation](./microsoftmovieanalysispowerpoint.pdf).

For any additional questions, please contact **Elliott Iturbe at eaiturbe@bsc.edu, Jacob Hoogstra at jnhoogstra@crimson.ua.edu, or Lorin Helfenstein at lehelfen@bsc.edu**

## Repository Structure

```
├── data                                  <- data files used for analyses
├── images                                <- visualizations created
├── Final Notebook.ipynb                  <- code written for project with explanation
├── microsoftmovieanalysispowerpoint.pdf  <- PDF version of powerpoint
└── README.md                             <- overview of project
```
