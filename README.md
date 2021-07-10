# Amazon Vine Analysis
Analyzing reviews for a bias towards positivity

## Overview

The goal of this analysis is to determine if paid reviews from the Amazon Vine program produce more 5 star reviews than 
from customers who were not paid for their reviews. 

I took the data from Amazon, and decided I was most interested in large appliances, because biased paid reviews is more
problamatic to me the higher the dollar amount of the purchase. In my opinion, it's more high stakes to buy a wash machine
than a video game. 

I then filtered the data by total votes to ensure I didn't have any divide by zero erros, because I then filtered by ratio
of helpful review votes to total votes. Since I'm interested in five star reviews that might have caused/influenced 
people to purchase, I filtered for 50% or higher helpful votes. 

I then split the data by vine reviews, and calculated the percentage of the data that was 5 stars, and will take my 
results from that. 

## Results

* Number of Vine Reviews: 35
* Number of NonVine Reviews: 4954
* Number of 5 Star Vine Reviews: 18
* Number of 5 Star NonVine Reviews: 1963
* Percentage of Vine Reviews at 5 Stars: 51.4%
* Percentage of NonVine Reviews at 5 Stars: 39.6%

## Summary

There appears to be a positivity bias towards reviews paid for in the vine program. 
There is an over 10% increase of 5 star reviews between paid and unpaid.

However, this needs to be further studied. Vine reviews are by far the minority 
of reviews in this category, and are so small that there might be some error due to
the small sample size. I would want to look at more categories of product reviews to 
look for a trend. 

I also want to do statistical analysis on whether the increase in 5 stars is actually 
statistically significant. I think a standard t test would be useful. 

