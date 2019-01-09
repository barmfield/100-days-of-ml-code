# 100 Days of ML Code Log

### Day 0: January 2nd, 2019

**Today's Progress**: After experimenting with a basic LinearRegression model
from sklearn, I decided to do a regression on the S&P 500 for the last five
years. I realized I needed to convert date strings from yahoo finance to
datetime objects, and spent most of my time writing a function to achieve this.


### Day 1: January 3rd, 2019

**Today's Progress**: I sucessfully converted string dates to floats and was
able to plot a regression line over the S&P. Next steps are to make the dates
visible on the x axis. One thing to remember going forward is that the data for
the x axis needs to be in a 2D array. It might be fun to create a website
where, using the yahoo finance api, a user could select any ticker for any time
period and plot a regression line on it. I used sklearn's LinearRegression
model, but I will explore other models where trend forecasting could be useful. 

Link: https://github.com/barmfield/100-days-of-ml-code/blob/master/linear_regression.ipynb

### Day 2: January 4th, 2019

**Today's Progress**: I refactored the code to work within a single function
so all a user has to do is download the notebook into their directory and a csv
from yahoo finance and can run the regression. I also added code to print the
training and testing accuracy. My new plan for a data science project is to
download data for all S&P 500 stocks and then run the regression and see which
has the highest test accuracy. This would indicate whether or not that stock
would be a good candidate for making trades based on a linear regression (under
low volatility conditions of course). 

### Day 3: January 5th, 2019

**Today's Progress**: After doing some extensive research on modeling stock
data with python, I realized I was trying to reinvent the wheel. Instead of
walking around like Sandra Bullock in Bird Box, I decided to start working on
the Udemy Course Python for Finance and Machine Learning. Today I worked my way
through some python and numpy exercises to learn more of the basics of data
manipulation in python. I hope to have some working prototypes using this
course soon. 

### Day 4: January 6th, 2019

**Today's Progress**: Writing from Jan. 7th as I neglected to update the log
yesterday. I spent the entire day practicing the numpy and pandas library.
I covered some of the most common and popular funcitons of each, and learned
how numpy is the foundation of the pandas series, which is the foundation of
the pandas dataframe. I will need to practice these concepts a lot to make them
stick, but already feel much more capabale of asking quesitons from data and
getting meaningful answers. I look forward to combining numpy and pandas with
matplotlib to create visualizations that I can share with others, and which I
can use to communicate results.

### Day 5: January 7th, 2019

**Today's Progress**: I spent today reviewing pandas, and then moved onto
matplotlib and the plotting functions of pandas. I finally learned how to plot
a stock chart directly from pandas, and am shocked at how difficult I was
making it for myself in earlier exercises. Sharpening the ax is starting to pay
off! 

### Day 6: January 8th, 2019

**Today's Progress**: I spent today working with and reviewing methods for time
series analysis with pandas. Using data from Quandl, I was able to create
several interesting stock charts, and finished the day by learning how to add
Bollinger Bands to a chart. Tomorrow, I will integrate everything I have
learned so far. 
