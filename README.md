# Amazon_Vine_Analysis

## Project Overview

The project included an analysis of paid Amazon reviews written by members of the paid Amazon Vine program. Our dataset initiated from the Videogame reviews, and we used PySpark in Google Colabto to perform the ETL process. Once our data was extracted, transformed and loaded, we had to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results

![](https://github.com/EnoVaqari/Amazon_Vine_Analysis/blob/main/Images/Results.png)

#### How many Vine reviews and non-Vine reviews were there?
* There is a total of 94 Vine reviews.
* There is a total of 40471 non-Vine reviews.


#### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* There is a total of 48 5-star Vine reviews.
* There is a total of 15663 5-star non-Vine reviews.


#### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* 51.1% of the Vine reviews were 5-stars.
* 38.7% of the Vine reviews were 5-stars.

## Summary

After conducting the analysis, we noted a positivity biases from the Vine program reviews due to the 51.1% of the 5-star Vine reviews compare to the 38.7% of the 5-stars non-Vine reviews. To have further visibility on the positivity biases, the analysis should include more information from the Vine Program.
