# Amazon_Vine_Analysis
## Objective
This challenge required the completion of the ETL process to load a dataset of Amazon reviews to pgAdmin in a postgreSQL schema. After completing the initial step for Deliverable 1, the challenge's primary objective was to perform an analysis on the dataset of Amazon reviews utilizing Pyspark and Google Colab to investigate if there was bias in the product reviews that had been written by paid advertising partners (Vine reviews) as opposed to reviews that were written by unpaid common folk (Non-Vine reviews). <br><br>The dataset selected for this analysis was comprised of a set of reviews for pet products. To ensure the integrity of the data, only reviews with 20+ ratings with 50% or greater positive ratings were retained prior to the bias analysis. The analysis of bias is to be performed by comparing the 5-star ratings as a percent of all ratings for both paid and unpaid reviews. 

## Results
### Counts of reviews
- Count of Vine Reviews<br><kbd>![Vine Reviews Count](Resources/paid_reviews_count.png)<kbd>
- Count of Non-Vine Reviews<br><kbd>![Non-Vine Reviews Count](Resources/unpaid_reviews_count.png)<kbd>

### Counts of 5-star reviews
- Count of 5-star Vine Reviews<br><kbd>![5-star Vine Reviews Count](Resources/paid_5star_reviews_count.png)<kbd>
- Count of 5-star Non-Vine Reviews<br><kbd>![5-star Non-Vine Reviews Count](Resources/unpaid_5star_reviews_count.png)<kbd>

### 5-star reviews as a percentage of all reviews
- Percent of 5-star Vine Reviews<br><kbd>![5-star Vine Reviews Percentage](Resources/paid_5star_reviews_percentage.png)<kbd>
- Percent of 5-star Non-Vine Reviews<br><kbd>![5-star Non-Vine Reviews Percentage](Resources/unpaid_5star_reviews_percentage.png)<kbd>
