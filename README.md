# Amazon_Vine_Analysis

## Overview
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.


### Total number of reviews

- Vine Reviews

![Vine_reviews (3)](https://user-images.githubusercontent.com/103701561/185807416-4f40c411-c6b5-4ed6-9d34-25bc3e11caf4.png)



- Non-Vine Reviews

![Vine_reviews (9)](https://user-images.githubusercontent.com/103701561/185807584-c32a5430-7f02-4e70-b02e-de6a1f124019.png)



### Total number of 5-star reviews


- Vine Reviews

![Vine_reviews (4)](https://user-images.githubusercontent.com/103701561/185807422-7ceb10bb-1901-4345-9dc4-7ecb099a20f5.png)


- Non-Vine Reviews

![Vine_reviews (6)](https://user-images.githubusercontent.com/103701561/185807434-c4f226e2-ac98-44e4-8b01-22d8edaf4f01.png)


### Percentage of 5-star reviews

- Vine Reviews


![Vine_reviews (5)](https://user-images.githubusercontent.com/103701561/185807430-34e82c08-0384-4fa7-a53b-db802b187132.png)


- Non-Vine Reviews


![Vine_reviews (7)](https://user-images.githubusercontent.com/103701561/185807436-c3866cc2-33ec-42b6-8a5f-5f20c1845352.png)


## Summary

51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyze the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.

