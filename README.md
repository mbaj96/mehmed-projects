# mehmed-projects
data analyst/data science personal projects

This repository contains a number of projects which I have worked on - generally analysing datasets to answer potential business questions the datasets pose. Analysis mostly performed using Python and libraries such as Scikitlearn, Matplotlib, Pandas and numpy - however there are also notebooks which use SQL entirely.

Below is a list of all the projects in this repository in order, along with a brief description of what the project entailed/the skills I used:


**Analysing CIA Factbook Data Using SQL**
Using SQL to query the CIA Factbook and answer some questions including:
* Which countries have above average population densities
* What is the average population and area of the Earth?
* Calculating water to land ratios for different countries, and finding the territories with the largest water/land ratio

**Analying NYC High School Data**
Using multiple datasets containing NYC High School SAT exam information to determine whether the SAT is a fair test
* Skills used include combining multiple datasets into one using Pandas
* Cleaning data
* Finding correlations between columns
* Data Visualisation using Matplotlib

**Answering Business Questions Using SQL**
Using SQL to obtain data from a relational database with 11 different tables containing information about a record store, to answer some questions about the data to identify new markets for the record store to break into
* Subqueries, aliasing of queries, case statements used extensively here.

**Building a Handwritten Digits Classifier**
Working with an dataset containing images of different digits - initially using the KNN algorithm to predict digits and then comparing with an ANN containing 1, 2, and 3 hidden layers to see if we can improve accuracy.  The ANN used was a multilayer perceptron (MLPClassifier module in scikitlearn).

**Building a Spam Filter with Naive Bayes**
Using a database of Spam messages to train our spam filter, which uses Bayes' Theorem to classify whether a message is spam or not by calculating the posterior proability of both of these events occurring, and seeing which event is more likely to occur.

**Cleaning and Analysing Star Wars Survey Results**
Using a survey dataset to identify whether Star Wars Episode V was the best film of the series by consensus.  The dataset was quite messy so lots of data cleaning was performed, alongside data visualisation using MatPlotLib to compare what different demographics thought of each film in the series.

**Cleaning and Analysing Employee Exit Surveys**
This project used two datasets containing survey data on employees - specifically information on each employee and their reasons for leaving their role.  This project aimed to answer two questions:
* Are employees who worked for the institutes for a short time resigning due to dissatisfaction? What about employees who have worked there longer?
* Are younger employees resigning due to dissatisfaction? What about older employees?
Lots of data cleaning was performed, alongside some feature engineeering to create a measure of employee dissatisfaction

**Exploring Hacker News Posts**
This project entailed comparing two different types of posts on Hacker News to determine which received more comments, and also whether posts created at a certain time received more comments.  Exploratory data analysis using Python, alongside working with the datetime library

**Exploring Ebay Car Sales Data**
Data exploration on a dataset from the German Ebay website - calculating information such as the average mileage and the average price for each brand of car.  Dataset is very messy so most of the project involved data cleaning.

**Finding the Best Markets to Advertise In**
Using a survey dataset to identify the best markets to advertise in for an e-learning company which creates online courses.  This project involved exploring the data and calculating how much respondents would spend on e-learning courses, based on the country they're from. Libraries used include Pandas, Numpy, Matplotlib, and Seaborn.

**Identifying Patterns in Jeopardy Questions**
The aim of this project was to clean and analyse a dataset containing past Jeopardy questions, with the aim of identifying any patterns in the questions that could be used to help future contestants win.  To do this, I identified how often answers are used for a question, investigating how often questions repeat in the dataset, and using a Chi Squared test to identify which terms correspond to high value questions.

**Investigating Fandango Movie Ratings**
A journalist named Walt Hickey analysed movie ratings data from a variety of different ratings websites and found evidence to suggest Fandango's rating system was biased.  Since the analysis was conducted quite a while ago, the aim of the project was to analyse more recent movie ratings data and determine whether there has been a change in Fandango's rating system.  This project involved using calculating the mean, median and mode of the ratings before and after Hickey's work - to determine whether there was a change.

**Mobile App for Lottery Addiction**
This project involved creating a number of functions that could be used in a hypothetical app, that problem gamblers can use to better estimate their chances of winning the lottery.  Lots of probability theory was used in this project, alongside printing outputs from the functions that are user friendly and easy to understand even for those that aren't familiar with probabilities.

**Predicting Bike Rentals Using Decision Tree Regressors**
The aim of this project was to predict the total number of bikes people rented in a given hour. This project involved some exploration to determine correlations between columns, alongside some feature engineering.  Lastly, I used a Decision Tree Regressor model and compared it to a Random Forest Regressor model by calculating the MSE of each model. 

**Predicting House Prices Using Multiple Linear Regression**
This project used a well known dataset containing information on houses in Ames, Iowa between 2006 and 2010. This project was quite involved and included some data cleaning and  feature engineering using functions I created to quickly transform columns.  The best features were selected based on their correlation with the Sale Price, and then the Multiple Linear Regression model was fit to the data and K-Fold Cross Validation performed to minimise the RMSE.

**Predicting Car Prices**
This project involved using the KNN algorithm to predict a car's market price, based on various features in the dataset.  Cross validation was performed in order to minimise the RMSE.

**Profitable App Profiles for the App Store and Google Play Markets**
My earliest project in this repository - it involved using Python with only the reader library to explore data and identify which kinds of apps are likely to attract more users. Of course this is much easier to perform using Pandas and Numpy but it taught me a lot about Python.

**Titanic - Machine Learning From Distaster Competition**
In this project the aim was to predict whether a passenger survived the Titanic accident or not. This project illustrates the entire data science workflow, from exploring the data, to cleaning the data, to engineering new features. I also used recursive feature elimination to select the most optimal features, alongside GridSearchCV to select the optimal hyperparameters for 3 different models, and find the model which has the best score.

**Visualising Earnings Based on College Majors**
This project entailed using data visualisation to answer questions on a dataset of job outcomes of students who graduated from college. Scatter plots, histograms and bar plots were used in this project.

**Visualising the Gender Gap in College Degrees**
This project aimed to visualise a dataset containing the percentages of men and women in different degrees, and how those have changed over time. 
