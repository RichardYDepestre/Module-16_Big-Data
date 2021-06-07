# Module 16 - Big Data
## Challenge: Amazon Vine Analysis
### Background
For this project, we have been asked to pick one dataset from the [Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) and submit it to an ETL process.
We will use technologies such as Pandas, Google Colab, Jupyter notebook, PostgreSQL, AWS to mine the dataset. By doing so, we intend to meet this challenge's requirements, namely: <br/>
- extract the dataset,
- transform the data, 
- connect to an AWS RDS instance, and 
- load the transformed data into pgAdmin.
Finally, using PySpark, Pandas, or SQL we will determine whether there exists any bias toward "favorable reviews from Vine members in the chsen dataset".
### Actions and Results<br/>
#### Actions
- Created a new database with Amazon RDS named [vinereviewdb](https://us-east-2.console.aws.amazon.com/rds/home?region=us-east-2#database:id=vinereviewdb;is-cluster=false),
- In pgAdmin, created a new database and linked it to Amazon RDS server,
- In pgAdmin created via a schema builder four tables to hold the data cleaned through our ETL process. These tables are: <ul><li>customers_table,</li> <li>products_table,</li> <li>review_id_table,</li> <li>and vine_table.</li></ul>
- Ran a script to populate these tables. The list below show the numbers of items loaded in each table:

|table name|count|
|---|-----|
|customers_table|3467883|
|products_table||
|review_id_table||
|vine_table|6221559|
 
#####  gfdgfga

#### Results
