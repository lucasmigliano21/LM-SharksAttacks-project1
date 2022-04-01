# Project 1: Global Sharks Attacks - Project 1

In order to start cleaning the data set, first we should import the attacks.csv file.
Once we execute .head(), we notice that columns' names have issues with 'spaces'. So we need to correct this problem by using .replace (regex).
Moreover, with some columns we need to use .rename() and another .replace() to correct typo problems.
Aftwerwards we check the number of nulls per columns. There are a lot! The simplest option is to replace all null values for 'unknown' values. For all the columns that do not have numbers, we can execute a .fillna('unknown') to replace the null values. We check this by executing code that shows only columns with null values, and if correct, we can continue.
