# Amazon Vine Analysis

## Overview

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

This project was focused on analyzing Amazon reviews written by members of the paid Amazon Vine program. 

A subset of approximately 50 datasets containing book reviews was extracted, then transformed using ETL process, connected to an AWS RDS instance, and loaded into pgAdmin. Next, Pandas was used to determine if there is any bias toward favorable reviews from Vine members.

## Resources
- Data Source: [Amazon Vine Reviews](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
- Tools: PySpark, AWS, pgAdmin

## Results

![Total Reviews](https://github.com/MariaGarzon/Amazon_Vine_Analysis/blob/ce87d625528ec6fce8ad289958470440676ed889/Images/Total_Reviews.png)

![Percent unpaid](https://github.com/MariaGarzon/Amazon_Vine_Analysis/blob/ce87d625528ec6fce8ad289958470440676ed889/Images/Percentage_Unpaid.png)

- Out of 403807 total reviews 60.15% of unpaid reviews are 5-stars. 
- Unfortunately, an analysis to determine the bias could not be made as the dataset contained 0 paid vine reviews. 

## Summary 
 
This project could not be used to draw a conclusion from our objective but the model can be implemented to other datasets and analysis that have a similar aim. 
