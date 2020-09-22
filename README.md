# Data_602

# Predicting Insurance Premiuim Cost for ABC Inc.

### Repository Navigation
<pre>
Technical Notebook         : <a href=https://github.com/Debanjan-C/Data_602/blob/master/Technical_Notebook.ipynb>Technical Notebook </a>
Code                       : <a href=https://github.com/Debanjan-C/Data_602/blob/master/Code.ipynb>Code</a>

</pre>

## Summary
ABC Inc. is a startup in the Washington DC area who has reached out to a health care insurance company to help them evaluate the premium based on multiple factors realting to each employees health and status. Generally, the region of the employees are calculated in insurance company, but in this case they most are based in the Washington DC area and therefore we will not be using that as a factor.Our datasets are the age, sex, bmi, # of children, smoker and the premium harges. The data has 1338 rows and 6 columns after we drop the region column. Otherwise, it was 7. Initially, We developed two training sets prior to that for testing and training using Scikit learn. After taht step, we developed linear regression models to calculate the premiums using scikit learn and stats model api that contains the Ordinary Least Squares model to calculate the r-squared and show the summary of the entire model with slopes, intercepts and all. Some of the main challenges were the outliers as multiple x values are there and it was difficult to choose how we could remove the outliers for one of them without affecting the other one. My R-squared value is 0.746 or 74.6% reliability of the x-variable which is somewhat reliable. The closer the value is to 1 the better.

## Business Goal and Overview
I work in a healthcare insurance company and other companies come and check how much premium would be provided for their employees. ABC Inc. is a Washington Dc metro based company. Their main issue is having trouble evaluating on the healthcare benefits of different employees as some have kids, some do not and there are many factors that go into each employees needs. They would like a prediction model to evaluate the premium each employee will be pay in the long run given their age, gender, bmi, # of children, if they smoke or not. Accordingly they will decide on health benefits package on how much they will cover and how much is out of pocket. They are based in this DC area and only operate here, so region field will not be calculated here. They have provided prior datasets to with those information and the premium paid.

In order to predict the premiuim cost of each employee, I used linear regression model and they will be using this for their calculation for the upcoming employees. I will be using supervised learning as we are given the labeled datasets and also will be developing test and training sets to check whether the overall regression model works. 

### Data
Dataset: https://www.kaggle.com/teertha/ushealthinsurancedataset
The individual who was using this Dataset in Kaggle was trying to predict the premium prices in the entire USA considering the different factors 

Columns: age, gender, children, smoker, charges. (Region field was dropped) So, dataset had 6 columns and 1338 rows

## Challenges & Limitations
I feel one of the challenge was the outliers part there were so many and it seemed that due to the fact that we had multiple x values, it was difficult to figure out where we can remove the outliers. If we look at the outliers with respect to x1 then I felt that we may get rid of some core data in another x value. Therefore, that was somthing I had difficulty with.

##  Conclusions
I feel that this model does evaluate we have a positive linear relationship when all of the x-values are taken into the model. However, I also feel that our residual plot and regression plots were not the best to evaluate the trends, but that is a plan to improve in the long run. Possibly, being able to evaluate which outliers or leverage points to remove, they may look relatively better. In general, medical insurance companies could look for more data into family medical history and other details. Those other factors could be taken into consideration next time. My R-squared value is 0.746 or 74.6% reliability of the x-variable which is somewhat reliable. The closer the value is to 1 the better.

<pre>
Contrubuter  : Debanjan Chowdhury
</pre>

<pre>
Languages    : Python
Tools/IDE    : Anaconda, Jupyter Notebook
Libraries    : pandas, matplotlib, seaborn, statsmodel api, scikit learn
</pre>

<pre>
Assignment Submitted     : September 2020
</pre>

<pre>
Dataset: <a href = https://www.kaggle.com/teertha/ushealthinsurancedataset</a>

</pre>
