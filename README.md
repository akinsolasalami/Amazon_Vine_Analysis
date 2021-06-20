# Amazon_Vine_Analysis

## Overview of the Analysis
I was tasked with analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. 

Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. I utilized PySpark and SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.

## Results

Total Reviews

![Image 4](Resources/image4.png "Image 4")

### How many Vine reviews and non-Vine reviews were there?

![Image 1](Resources/image1.png "Image 1")

* The wireless dataset had a total of __613__ vine (paid) reviews

* The wireless dataset had a total of __64968__ no-vine (unpaid) reviews

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![Image 2](Resources/image2.png "Image 2")

* The wireless dataset had a total of __222__ vine (paid) 5-star reviews

* The wireless dataset had a total of __30543__ no-vine (unpaid) 5-star reviews

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![Image 3](Resources/image3.png "Image 3")

* __36.22%__ of the Vine reviews were 5-stars

* __47.01%__ of the non-Vine reviews were 5-stars

## Summary
From our analysis, there is not a bias towards the Vine (paid) reviews. From the 613 paid reviews only 222 were 5-star which is around 36%. There were more unpaid reviews and a higher percentage of those reviews were 5-star. Hence, it is not worth to pay for the reviews. There is no bias. 

An additional analysis would be to seprate the different products and see how the vine reviews affect different wireless products. Some wireless devices might be more susceptible to advertising and paid reviews.
