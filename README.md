# Big Data on Amazon Reviews

## Background

This project is analyzing amazon reviews on video games and luggage. Each dataset contains over 1.5 million rows. The ETL process was performed completely in the cloud, and the DataFrame was uploaded to an RDS instance. Basic statistical analysis was also performed on one of the datasets.

## Level 1
The setting up of AWS RDS and correctly connecting to local postgresql pgAdmin is the most challenging part of this project. **The ETL** process is:
* Use the schema to create tables in the RDS database with [Google Colab notebnooks](https://colab.research.google.com/notebooks/) and **extract** two datasets from the list at review dataset, one into each notebook.
* **Transform** the dataset to fit the tables in the schema file.
* **Load** the DataFrames that correspond to tables into an RDS instance.


## Level 2

This part is to check if there is a bias of amazon Vine reviews: https://www.amazon.com/gp/vine/help?ie=UTF8.

The comparison of mean and standard deviation was calculated on both vine reviews and non-vine reviews. The vine reviews have higher averages than non-vine averages based on analysis. The t-test results show that the two ratings have statistical differences.


## References

Amazon customer Reviews Dataset. (n.d.). Retrieved April 08, 2021, from: [https://s3.amazonaws.com/amazon-reviews-pds/readme.html](https://s3.amazonaws.com/amazon-reviews-pds/readme.html)

- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
