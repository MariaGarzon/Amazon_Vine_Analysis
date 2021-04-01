# Amazon Vine Analysis

## Overview

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

This project was focused on analyzing Amazon reviews written by members of the paid Amazon Vine program. 

A subset of approximately 50 datasets containing book rewviews was extract, then transformed using ETL process, connected to an AWS RDS instance, and loaded into pgAdmin. Next, Pandas was used to determine if there is any bias toward favorable reviews from Vine members.

## Resources
- Data Source: [Amazon Vine Reviews](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
- Tools: PySpark, AWS, pgAdmin

## Results

- 51.06% of paid reviews are 5-stars and 38.7% of unpaid reveiws are 5-stars.

## Summary 
