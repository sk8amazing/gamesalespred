# Video Game Sales Prediction - ML Project
The Project is Coded for Machine learning Course and it is studied by (Prof.Lorenzo Rosasco, Prof.Alessandro Verri) in Univerity of Genova,italy 2018/2019

This project is predicting the video games sales in several different Area and it is coded in python.

project is a supervised-Regression.

#  Data Set 

After search in kaggle I found several game related data sets but i choosed to take the video games sales for predicting the sales . 
first of all I had to pre-process the data set I choosed then use the algorithms : SVM (support vector machines) , Linear Regression 
and in the final we have accuracy and cross validation values.
.csv format file and it contains 16500 rows and 11 column, the number for each sales are defined as million dollar.

JP = JAPAN SALES

EU = EUROPEAN SALES

NA = NORTH AMERICA SALES

GLOBAL SALES = SALES AROUND THE WORLD

PUBLISHER = THE COMPANY MADE A GAMES

SALES = IN MILLION DOLLAR

PLATFORM = Release platform for the game

YEAR = Year of release (Since 1980 to 2016)


# Steps of Project 
1- Data Pre-Processing

2- Implementing the Algorithms

3- Results

# Data Pre-Processing
Data set Link : https://www.kaggle.com/gregorut/videogamesales
with 16579 rows for each 11 column.

1-First step is loading the data set in program you want to write the codes , for me it is a jupiter note book of anaconda 
(www.anaconda.com)

2-the second part I start to find how many null we have so with the code we find how many of our datas in which column are null and then after we found that out 
which type of data is null we can do the right action for example in this dataset I have nulls in my "Year" column and we have two option to 
set a mean of all other years into null and the other option is if our null data is not that much in compare of our rows  we can delete entire the rows with null data but this is not a good option and 
it will change the results dramatically


3-in this part I want to convert names of games which is categorical into a numerical because work with categorical inputs is difficalt and most of times not possible.


4-so, in the next part I drop the columns which i dont want to use with
and the main purpose of drop for me is because my laptop is so old and process will take more times.
beside of drop some column I add some code to drop some of data from buttom because of the old laptop , so can delet that part.

5-its time for choosing Features X and Labels Y
I choose the name of games as X and the mount of their sales as Y.

6- in this part I splite the data set into Training and Test sets.

# Implementing the Algorithms

1-Linear Regression

2-SVR ( SUPPORT VECTOR MACHINES )


 

# Results

Linear regression : 

                    cross-validation 68%

                    accuracy 73%
                    
SVR               : 

                    cross-validation 57%

                    accuracy 58%           
                    
 
