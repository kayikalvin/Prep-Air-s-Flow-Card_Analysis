# Prep-Air-s-Flow-Card_Analysis
This project ias a continuation of [Prep-Air-s-Flow-Card](https://github.com/kayikalvin/Prep-Air-s-Flow-Card)
This week the challenge will involve unions, aggregation and reshaping data.

## Requirements
a. Input the two csv files<br>
b. Union the files together<br>
c. Convert the Date field to a Quarter Number instead<br>
            * Name this field Quarter<br>
d. Aggregate the data in the following ways:<br>
            * Median price per Quarter, Flow Card? and Class<br>
            * Minimum price per Quarter, Flow Card? and Class<br>
            * Maximum price per Quarter, Flow Card? and Class<br>
e. Create three separate flows where you have only one of the aggregated measures in each.<br> 
            * One for the minimum price<br>
            * One for the median price<br>
            * One for the maximum price<br>
f. Now pivot the data to have a column per class for each quarter and whether the passenger had a flow card or not<br>
g. Union these flows back together<br>
h. What's this you see??? Economy is the most expensive seats and first class is the cheapest? When you go and check with your manager you realise the original data has been incorrectly classified so you need to the names of these columns.<br>
i. Change the name of the following columns:<br>
            * Economy to First<br>
            * First Class to Economy<br>
            * Business Class to Premium<br>
            * Premium Economy to Business<br>
