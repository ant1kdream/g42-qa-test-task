
## Task:
Please create as many as possible functional tests for the data provided in the file "elastic_data.json" using pytest (pytest is mandatory).  
This file contains demo data from elastic search, in total 4675 records capturing purchases of different users. 
All fields in "elastic_data.json" are mandatory except of "geoip.region_name" and "geoip.city_name". Your solution must be uploaded to github.


### Additional info:
Tests should check that the data is correct and exist, i.e. an email field contains '@' and a domain is a valid domain, not empty; customer_first_name is valid and does not have int values. And so forth, not to limit yourself only to these examples, open up your imagination and destructive (verification) powers.

There is no need to parametrize for every record in elastic_data because in this case you will receive total amount of tests = 4675 * amount of your created tests.
We recommend you to group tests by any field you might consider.  

An example of possible tests grouping. Let's say we have a task to test every customer feedback on an e-commerce website, for multiple products. Suppose, that we have 200 different feedback records for every product and 20 products, total 200 * 20 = 4000 feedback records across all products. 

In this case, it would be better to group tests by product names, and after parametrization we would have 20 different groups, each test would run checks for 200 records for every product, and we would see ids of the failed records in the output.

You are also free to use your own way to group data.