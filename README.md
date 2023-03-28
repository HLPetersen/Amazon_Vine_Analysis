# Amazon Vine Analysis #

## Overview of Analysis ##
Amazon vine is a service that allows companies to provide products to customers for reviews for a fee. Amazon has datasets on reviews for different types of products. The review set chosen was of pet products https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Pet_Products_v1_00.tsv.gz . There are tens of thousands of reviews.  Each review entry contained the following information:

<img width="600" alt="overview" src="https://user-images.githubusercontent.com/116980760/228119450-d2981f62-8f12-4197-baa5-79339e33893b.PNG">

## Purpose of Analysis ##
The purpose of this analysis is to determine whether or not there is a strong positive bias in Amazon vine reviews versus those from unpaid customers. The percentage of 5 star ratings will be compared for both vine reviews and unpaid reviews. 

## Results ##
- There were 170 vine reviews and 37,840 unpaid reviews.
- The vine reviews had 65 5 star reviews.
- Th unpaid reviews had 20,612 5 star reviews
- This translates to 38% of the vine reviews were 5 star whereas 54% of unpaid reviews were 5 star.
<img width="326" alt="percentages" src="https://user-images.githubusercontent.com/116980760/228110374-d42265f3-2794-4a96-94a7-5d2219434b69.PNG">

## Summary ##
The percentage of positive reviews was much higher for unpaid reviews. 
It would be interesting to see the breakdown of the percentage for each star rating. If 4 star reviews show unbiased positive results as well, then 
it could be more conclusively stated that there is no bias. 
