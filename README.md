# Amazon_Vine_Analysis

## Purpose of the Project

The purpose of the analysis is to provide the product reviews information to publishers. The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics. Vine members are paid for their reviews, with the analysis it can be determined if the compensation is providing us a bais reviews.

## Results

The results obtained from the analysis are the following:

**Including all Reviews**

- Total Number of Reviews: 50,753
- Total 5 Star Reviews: 23,497
- Percentage of Total 5 Star Reviews: 46.29%

**Vine Reviews**
- Total Number of Vine Reviews: 1,080
- Total 5 Star Vine Reviews: 454
- Percentage of 5 Star Vine Reviews: 42.04%

**No-Vine Reviews**
- Total Number of non-Vine Reviews: 49,673
- Total 5 Star non-Vine Reviews: 23,043
- Percentage of 5 Star non-Vine Reviews: 46.39%


## Summary

Based on the analysis of the product reviews, it can be conclude that there is no evidence that there is any bias in positive reviews for the Vine program. The rate of 5 Star reviews is lower for Vine members **(42.04%)** than the non-Vine members **(46.39%)**.

To obtain a more elaborated review of the product, an additional analysis on the dataset would be the analysis of the words used by the reviewer in the comment section column, this could add a more complete set of subjective data to analyze.
