# Big Data on Amazon Reviews

## Background

This project is analyze amazon reviews on vidoe games and lugguges. Each of the dataset contains over 1.5 million rows. The ETL process was performed completely in the cloud and the dataframe was uploaded to an RDS instance. Basic statistical analsis was also performed on one of the dataset.

### Level 1

* Use the schema to create tables in the RDS database with Google Colab notebooks and **extract** two datasets from the list at [review dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt), one into each notebook.

* **Transform** the dataset to fit the tables in the [schema file](../Resources/schema.sql).

* **Load** the DataFrames that correspond to tables into an RDS instance. 

### Level 2 

This part is to check if there is bias of amazon Vine reviews: [https://www.amazon.com/gp/vine/help?ie=UTF8](https://www.amazon.com/gp/vine/help?ie=UTF8).

The vine reviews have higher averages than non-vine averages. The comparison of mean and standard diviation were calculated on both vine reviews and non-vine reviews. The t-test results shows that the two ratings have statistical differences.


## References

Amazon customer Reviews Dataset. (n.d.). Retrieved April 08, 2021, from: [https://s3.amazonaws.com/amazon-reviews-pds/readme.html](https://s3.amazonaws.com/amazon-reviews-pds/readme.html)

- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
