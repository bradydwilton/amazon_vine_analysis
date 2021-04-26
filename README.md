# Amazon Vine Analysis

## Overview of the Analysis
Use PySpark to determine if there is any bias toward paid reviews created by Vine versus unpaid reviews.

## Results
The following dataframe answers the following questions about the data:
* How many total reviews (Vine and non-Vine) are in the dataset?
* How many 5-star reviews (Vine and non-Vine) are in the dataset?
* What percentage of Vine and non-Vine reviews are 5-star?

<img src='https://github.com/bradydwilton/amazon_vine_analysis/blob/main/images/vine_stats_dataframe.png'>

## Summary
The data shows that paid Vine reviews, which are far fewer in number than the unpaid reviews, have a lower percentage of 5-star reviews than the unpaid reviews d0. Further analysis on other categories should be done in order to determine if this is consistent across Amazon's platform or specific to the baby item category.