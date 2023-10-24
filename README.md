# Home_Sales

In this challenge, I 'll use SparkSQL to determine key metrics about home sales data. Then i'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

# Dataset

[AWS S3 BUCKET](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv)

![bd](https://github.com/dilqvl62/Home_Sales/assets/107519883/fadb04fb-e06d-4aa8-a3ef-aa79b492214f)

## Objectives

*  Answer the following questions using SparkSQL:

    * What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
 
    * What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
    
    * What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
    
    * What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

* Cache your temporary table home_sales.

* Check if your temporary table is cached.

* Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

* Partition by the "date_built" field on the formatted parquet home sales data.

* Create a temporary table for the parquet data.

* Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

* Uncache the home_sales temporary table.

* Verify that the home_sales temporary table is uncached using PySpark.


