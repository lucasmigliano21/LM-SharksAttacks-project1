https://static.scientificamerican.com/sciam/cache/file/44782A7E-8025-4A62-833DC6E4CF9A42CB_source.jpg?w=590&h=800&894CEEE1-0BE8-4122-A713699037806AFF
# Project 1: Global Sharks Attacks - Project 1

In order to start cleaning the data set, first we should import the attacks.csv file.
Once we execute .head(), we notice that columns' names have issues with 'spaces' and another characters. So we need to correct this problem by using .replace (regex), and also with .rename .
Aftwerwards we check the number of nulls per columns. There are a lot! The simplest option is to replace all null values for 'unknown' values. For all the columns that do not have numbers, we can execute a .fillna('unknown') to replace the null values. We check this by executing code that shows only columns with null values, and if correct, we can continue.
On the other side, we can change the data type of original_order column from float64 to int64, just to show we can.
The we can do the same with the last columns, to fill all the blank spaces with "unknown".
Finally export the csv, checking that we used more than 5 types of cleaning options, also that the number of columns is > 20K.

We can now focus on the bonus questions. USA is the country where more attacks were registered; 2015 was the year with most attacks registered globally; in comparison, sharks tend to attack 5x to men than women; finally more than twice of the attacks were not fatal.
