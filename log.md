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
