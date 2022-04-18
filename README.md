# Amazon_Vine_Analysis
Module 16: Big Data
###### Project Overview
- Use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin
- Use PySpark, ***OR*** Pandas, ***OR*** SQL to determine if there is any bias toward favorable reviews from Vine members

###### Resources

Pet Product Reviews Data Set [amazondataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Pet_Products_v1_00.tsv.gz)

###### Results - Deliverable 2

![helpfulvotescount](https from github)

- Helpful Votes greater than 50% = 38010

![vinereviewscount](https from github)

- Vine Reviews = 170
- Non-Vine Reviews = 37840

![vinestarcount](https from github)

- Vine 5 Start Count = 65
- Non-Vine 5 Start Count  = 20612

![vinepercent](https from github)

- Vine 5 Start Percentage = 38.235294%
- Non-Vine 5 Start Percentage = 54.471459%

###### Results - Deliverable 1

![customers_table](https from github)
![customers_table_sql](https from github)
![products_table](https from github)
![review_id_table](https from github)
![vine_table](https from github)
![sql_tables](https from github)

###### Summary
- The analysis is biased towards unpaid Vine reviews
- 50% of helpful votes may have been too large for paid Vine reviews. I suggest using all paid vine reviews to determine satisfaction levels. This may give insight to why most reviews an unpaid. 