# Amazon_Vine_Analysis

# Project Overview:
An analysis of bigdata using PySpark, pgAdmin, and AWS to determine bias in product reviews.


## Resources:

* Data Sources: amazon_reviews_us_Musical_Instruments_v1_00.tsv

* Software: pySpark, pgAdmin, and AWS

## Results:

* How many Vine reviews and non-Vine reviews were there?

- There were 60 Vine reviews.
- There were 14,477 non-Vine reviews.

<img width="649" alt="Screen Shot 2022-04-08 at 3 02 51 PM" src="https://user-images.githubusercontent.com/93015602/162540899-9287a339-c0e6-4d82-820b-65f054603f1a.png">

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- There were 34 5-star Vine reviews.
- There were 8212 5-star non-Vine reviews.

<img width="764" alt="Screen Shot 2022-04-08 at 3 17 00 PM" src="https://user-images.githubusercontent.com/93015602/162540912-cfd9f74b-6e30-4df1-983a-f3c565e1f876.png">

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- 56.66% of Vine reviews were 5-stars.
- 56.72% of non-Vine reviews were 5-stars.

<img width="688" alt="Screen Shot 2022-04-08 at 3 12 12 PM" src="https://user-images.githubusercontent.com/93015602/162540907-794e8c0c-3e6d-4560-8943-3979489057ea.png">


## Summary:
Upon review of the data, there does not appear to be positivity bias for reviews in the Vine program as both paid and non-paid reviews have 5-star ratings of approximately 57% and the majority of reviews are non-paid as opposed to paid.  A two-sample t-test could be utilized to determime if the number of 5-star reviews is statistically different between paid Vine reviews and non-Vine reviews. In addition, the number of 1 star reviews between paid and non-paid could also be evaluated to determine if a statistically significant difference exists. 