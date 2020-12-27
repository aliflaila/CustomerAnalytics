# CustomerAnalytics

Objective:-
The *aim* of the project was to conduct analysis on the client’s transaction dataset and identify customer purchasing behaviours to generate insights and provide commercial recommendations. To present a strategic recommendation that is supported by data we need to analyze the data to understand the current purchasing trends and behaviours.

Input:-
The input includes two datasets i.e transaction data and the purchasing behaviour for a span of a year.

We begin by performing high level data checks such as:
Creating and interpreting high level summaries of the data
Finding outliers and removing these
Checking data formats and correcting them

We notice that the date column has data type of integer we will convert it to datetime for ease in further analysis. Post this we perform a left join on both tables to merge them.
A quick check on the data tells us that data is missing for 25th December 2018, this could be because stores are closed for Christmas.




