# Amazon_Vine_Analysis

## Overview of Project
The purpose of this analysis is to determine whether or not there was a signifcant difference in the number of 5-star reviews of products that had a paid Vine review, versus those that did not have a review. For the sake of scope of the analysis, the product keyed in on was luggage. The analysis was done using Pyspark and data was collected via Amazon Web Services. 

## Results 
- How many Vine reviews and non-Vine reviews were there? 
There were 21 Vine reviews, and 6,309 non-Vine Reviews.

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
Ten Vine reviews were five stars, and only 11 non-Vine reviews were 5 stars.

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
47.61 and 0.17 respectively. 

## Summary
While the sample size of the Vine reviewed product is limited. There is clearly a bias when a product has been reviewed on the Vine app. Nearly half of the reviews were five stars, while only of eleven of the non-Vine reviews were. A difference of just one. Additionally the data set contains metrics on how helpful a review was. Helpfulness could be seen as auxillarly variable for credence of a review. One could see if the five star reviewed Vine products had actually helpful reviews. If they were not helpful, it would indicate possibly that the product was simply reviewed well because it was seen on an app, and not because of its inherent quality as a product.
