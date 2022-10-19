
## Task:
Please create validation tests (tests checking that data is correct and exist) on the data provided in the file "elastic_data.json" using pytest. This file contains demo data from elastic search, in total 4675 records capturing  purchases of different users. 


### Additional info:
There is no need to make separate 4675 tests, you can group tests by field "geoip.city_name" for the records where this field exists, and separate group with "unknown city" where field is absent. You are also  free to use your own way to group data. All fields in "elastic_data.json" are mandatory except of "geoip.region_name" and "geoip.city_name". Your solution must be uploaded to github.
