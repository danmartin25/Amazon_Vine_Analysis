# Amazon Vine Analysis

## Overview of the Analysis
We have been tasked with at project to analyze Amazon reviews written by members of the paid Amazon Vine Program. We will be using PySpark, Amazon Web Services, Google Colab, and SQL via pgAdmin to analyze the data set. Specifically, we will be using the sports reviews from https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Sports_v1_00.tsv.gz .

## Results

### How many Vine reviews and non-Vine reviews were there?
- There were 334 Vine reviews and 61,614 non-Vine reviews.

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- There were 139 Vine reviews with 5 stars and 32,665 non-Vine reviews with 5 stars.

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 41.62% of Vine reviews were 5 stars and 53.02% of non-Vine reviews were 5 stars.


Results in Google Colab:

![results](https://user-images.githubusercontent.com/91795475/152668984-7bf4dbb4-4f39-4c1c-98df-6a1cf43e74c8.png)


## Summary

Based on the data, I would theorize that there is no positivity bias in the reviews for the Vine program. The reviews for the vine program are actually about 10% lower for five stars than reviews that were non-Vine. This difference may indicate that there is a negativity bias, but the smaller sample size for Vine reviews gives us reason for caution. I would recommend doing a statistical test (a t-test may be best) to determine if the sample size is large enough to make the conclusion that there is a negative bias for the Vine program (or a positive bias for non-Vine reviews).
