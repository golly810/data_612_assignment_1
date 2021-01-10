# data_612_assignment_1
Assignment #1 for Franklin Data 612 - Data Mining 

In this assignment, I decided to use the Stocks data. After importing the csv from the link for the class repository I printed the head and tail. I was unsure if we were supposed to use the print function or just call head and tail so I used print for the initial and used df.head(10) and df.tail(10) to specify larger numbers of the first 10 and last 10 elements. Using the columns attribute, I pulled the 19 columns. As I imported pandas and used read_csv, we can see that the type is a DataFrame. I used both shape and info() as two different ways to show the number of rows and columns (67905, 19). Finally I used groupby() and mean()on both one column calls and lists of multiple columns. 
