# Amazon_Vine_Analysis

## Overview of the analysis
Using Pyspark we are able to download Amazon review data and create tables in PgAdmin. We are also able to do this by running the server on AWS. Our calculations were done using Pyspark.

## Results

#### How many Vine reviews and non-Vine reviews were there?
By checking the total paid and unpaid reviews we can see that there are 607 paid and 50522 unpaid reviews.
![Reviews](Images/total_paid_unpaid.png)


#### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
We can also see that 257 are paid reviews and 25220 are unpaid. This shows that a majority of the 5 star users enjoy the product.
![Reviews](Images/five_star_totals.png)

#### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
We can see that 42% of 5 star reviews are paid while 49% are unpaid. 
![Reviews](Images/percentage.png)

## Summary: 
There does not seem to be bias at least in the camera section we checked. As the avergae shows that about half unpaid users did enjoy the products. We can further review this by looking at 1 star or 2 star ratings and seeing if the displeasure finds a similiar comparison.
