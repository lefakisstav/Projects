Energy Utilities Customer Analysis

Overview

Exploratory and predictive analysis of an anonymized energy-utilities
customer dataset. The presentation covers customer profile, behavior,
digital engagement, payment timing, correlations, and customer
segmentation.

Dataset

https://www.kaggle.com/datasets/jamespauls/energy-utilities-application-data

-   Simulated/anonymized utilities customer data
-   Based on 2014--2017 consumption data from utilities-company training
    datasets
-   Includes energy usage, customer characteristics, application/usage
    data, and web/mobile activity

Main Analysis

-   Customer tenure and acquisition trends
-   Demographic and household profile
-   Energy consumption and home area
-   Payment behavior and days to pay
-   Mobile and web engagement
-   Correlation analysis
-   Customer profile clustering



Key Findings

-   Median customer tenure is 1.4 years.
-   2016 was the strongest customer-growth year, with more than 1,000
    new customers; growth slowed substantially in 2017.
-   Married customers form the largest customer segment.
-   60% of customers have a Bachelor's degree or higher.
-   Larger homes are associated with higher energy consumption.
-   Most customers live in homes below 200 m² and consume below 50
    units/day.
-   73% of customers pay late; most late payments are only 1--5 days
    late.
-   Mobile is the dominant digital engagement channel.
-   Web and mobile usage are largely independent.
-   Payment timing shows no meaningful correlation with consumption,
    area, or overall engagement.
-   Mobile engagement shows a non-linear relationship with payment time,
    while higher web visit frequency is generally associated with longer
    payment times.


Modeling

Customer segmentation was explored using:

-   **DBSCAN** --- density-based clustering and assessment of natural
    customer groups.
-   **K-Means** --- partitioning customers into profile-based clusters.

The presentation compares the approaches and reports the resulting
customer profiles.


