# mod2linear_regression

## Synopsis

The goal of my project was to predict which attributes of a diamond affect the price of the diamond the most and predict the trajectory of the prices of the diamonds. I used data from James Allen online diamond store to gather attributes of their diamonds and also pull their price. Luckily i was able to get a csv file, and import that into a data frame. I needed to clean some of the data to get the variables into useful information. Since i am predicting a diamonds price, and its attributes are based on alot of ordinal values, i needed to change alot of the variables to take into account that it has ordinal value when running linear models. We collected carat, color, clarity, cut, authentication(lab-approved), origin of diamond(lab-grown or naturally farmed), price, shape.

### What I Found out

So according to the data, the highest contributors to the price of the diamond, was the 4Cs or better known as (carat,color,clarity, and cut) but it seems like the origin of the diamonds whether it was lab-grown or naturally farmed came in second highest contributor to the price. If you take away the 4Cs and origin, the shape of the diamonds really starts to affect the pricing.

### If i had more time

I would like to work with figuring out a way to incorporate the diamond colored csv. Originally i wanted to do all types of diamonds, whether it was clearless, pink, blue, canary, and so forth but unfortunatly i didn't have time, because the colored diamonds had more attributes compared to the clearless diamond set.

## My Files

### model_processing.ipynb

model_processing has all my calculations of where I did all my linear regression models and 

my linear model
my lasso model
my ridge model
my f-test model
OLS models that so the coef of price/features


### working_with_data.ipynb

Cleaning/reforming data
creating new variables
creating plots and charts to analyze data
Changing existing variables accordingly
observation of the data
heatmaps

### diamonds_no_color.csv

webscrapped csv file of diamonds(clear colored)

### diamonds_no_color.csv

revised csv file of diamonds_no_color to run linear models in model_processing.ipynb

### diamonds_color.csv
extra dataset of diamonds with different color
could be a future project
unused csv in model_processing or working_with_data
