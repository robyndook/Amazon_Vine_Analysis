# Amazon_Vine_Analysis
Module 16: Big Data
###### Project Overview
- Use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin
- Use PySpark, ***OR*** Pandas, ***OR*** SQL to determine if there is any bias toward favorable reviews from Vine members

###### Resources

Pet Product Reviews Data Set [amazondataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Pet_Products_v1_00.tsv.gz)

###### Results - Deliverable 2

![helpfulvotescount](https://github.com/robyndook/Amazon_Vine_Analysis/blob/ce97be024d351297bb64c3645072d02521de7dd8/Images/2022-04-18_09-59-47.jpg)

- Helpful Votes greater than 50% = 38010

![vinereviewscount](https://github.com/robyndook/Amazon_Vine_Analysis/blob/ce97be024d351297bb64c3645072d02521de7dd8/Images/2022-04-18_09-20-03.jpg)

- Vine Reviews = 170
- Non-Vine Reviews = 37840

![vinestarcount](https://github.com/robyndook/Amazon_Vine_Analysis/blob/ce97be024d351297bb64c3645072d02521de7dd8/Images/2022-04-18_09-21-30.jpg)

- Vine 5 Start Count = 65
- Non-Vine 5 Start Count  = 20612

![vinepercent](https://github.com/robyndook/Amazon_Vine_Analysis/blob/ce97be024d351297bb64c3645072d02521de7dd8/Images/2022-04-18_09-24-35.jpg)

- Vine 5 Start Percentage = 38.235294%
- Non-Vine 5 Start Percentage = 54.471459%

###### Results - Deliverable 1

![customers_table](https://github.com/robyndook/Amazon_Vine_Analysis/blob/ce97be024d351297bb64c3645072d02521de7dd8/Images/2022-04-16_13-24-30.jpg)
![customers_table_sql](https://github.com/robyndook/Amazon_Vine_Analysis/blob/ce97be024d351297bb64c3645072d02521de7dd8/Images/2022-04-18_09-14-57.jpg)
![products_table](https://github.com/robyndook/Amazon_Vine_Analysis/blob/ce97be024d351297bb64c3645072d02521de7dd8/Images/2022-04-16_13-25-35.jpg)
![review_id_table](https://github.com/robyndook/Amazon_Vine_Analysis/blob/ce97be024d351297bb64c3645072d02521de7dd8/Images/2022-04-16_13-26-06.jpg)
![vine_table](https://github.com/robyndook/Amazon_Vine_Analysis/blob/ce97be024d351297bb64c3645072d02521de7dd8/Images/2022-04-16_13-26-33.jpg)
![sql_tables](https://github.com/robyndook/Amazon_Vine_Analysis/blob/ce97be024d351297bb64c3645072d02521de7dd8/Images/2022-04-18_10-07-10.jpg)

###### Summary
- The analysis is biased towards unpaid Vine reviews
- 50% of helpful votes may have been too large for paid Vine reviews. I suggest using all paid vine reviews to determine satisfaction levels. This may give insight to why most reviews an unpaid. 
