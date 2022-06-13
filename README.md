# Amazon_Vine_Analysis

ETL and meta-analysis of Amazon Vine reviews with AWS, postgresql, PySpark, and Google Colab

# Overview

The goal of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
 
 For this project I reviewed two datasets; the first one pertaining to Amazon reviews of watches, and the second one reviews of health personal care products.The initial ETL portion of the project was conducted, as prescribed, using AWS, postgresql, and PySpark in Google Colab. The data analysis segment was conducted using PySpark and Google Colab.

# Results

I filtered the available reviews to just those with more than 20 votes, and those which were more than 50% "helpful."

![vine_filtered_votes_df](https://user-images.githubusercontent.com/95712234/173296027-f98c3d01-5067-40b5-85c0-5049c2eaead9.png)

Based on this filtered dataset, I made the following calculations:

![Calculations #1](https://user-images.githubusercontent.com/95712234/173296391-ef48e0fa-eaf1-427d-b4d9-bac9b8e24783.png)

![Calculations #2](https://user-images.githubusercontent.com/95712234/173296419-0f3702b3-ce0f-41f0-9206-94f4b6197839.png)

