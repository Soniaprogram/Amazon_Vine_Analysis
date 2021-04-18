# Amazon_Vine_Analysis

Deliverable 1: Perform ETL on Amazon Product Reviews

Deliverable 2: Determine Bias of Vine Reviews

Deliverable 3: A Written Report on the Analysis (README.md)


## Overview of the analysis

I have been tasked with analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Using my knowledge of PySpark, I determined if there is any bias towards reviews that were written as a part of the Vine program. For this analysis, I determined if having a paid Vine review makes a difference in the percentage of 5-star reviews.


## Results

* How many Vine reviews and non-Vine reviews were there?

  There were 94 Vine (paid) reviews. There were 40,471 non-Vine (unpaid) reviews.

  ![img1](https://github.com/Soniaprogram/Amazon_Vine_Analysis/blob/main/images/1paidnumber.PNG)
  ![img2](https://github.com/Soniaprogram/Amazon_Vine_Analysis/blob/main/images/1unpaidno.PNG)


* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

  There were 48 Vine (paid) 5-star reviews. There were 15,663 non-Vine (unpaid) 5-star reviews. 

  ![img3](https://github.com/Soniaprogram/Amazon_Vine_Analysis/blob/main/images/2fivestarpaid.PNG)
  ![img4](https://github.com/Soniaprogram/Amazon_Vine_Analysis/blob/main/images/2fivestarunpaid.PNG)

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

  38.7% of non-Vine (unpaid) reviews were 5-stars. 51.1% of Vine (paid) reviews were 5-stars. 

  ![img5](https://github.com/Soniaprogram/Amazon_Vine_Analysis/blob/main/images/3fivestarpaidpercent.PNG)
  ![img6](https://github.com/Soniaprogram/Amazon_Vine_Analysis/blob/main/images/3fivestarunpaidpercent.PNG)


## Summary
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

It seems as though 51.1% of the Vine reviews were 5-stars which is greater than the non-Vine 5-star review percentage of 38.7%. Paid members seemed more likely to provide a 5-star review, which also might explain why they purchased a paid membership in the first place. 
In order to further explore this bias, I would look into how long the Vine users have been members of this service vs how long the non-Vine users have been members of this service as well. It would also be beneficial to look at the average/mean number of stars for both Vine and non-Vine reviews.
