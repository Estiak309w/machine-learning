# Yelp Business rating predittion #
## tools and library ##
Jupyter Notebook, pandas, scikit learn
## Dataset Description ##
This dataset contains 10000+ data with 5 classes.Text column contains user's review and stars column contains numeric label data from 1 to 5.

## Project Description ##
This project predict text review data to star. Based on review it predict whether the reivew will good,bad,worst,average or excellent by categorizing from 1 to 5. 75% of data are used to train and 25% of data are used to test.**multinomial Naive Bayes** and **logistic Regression** are used to classify the data. where **multinomial naive bayes** provide better accuracy **49.60%**. At a first glance , it may seems the accuracy is quite low. but, for such a multiclass classification with only 10 thousands of data  it provide quite better performance.
