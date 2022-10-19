
## Task:
Please create validation tests (tests checking that data is correct and exist) 
on data provided in file "elastic_data.json" using pytest. This file consist of fetched demo 
data from elastic search that contains 4675 records about purchased that was provided by different users. 

### Additional info:
There is no need to make separate 4675 tests, you can group tests by field "geoip.city_name" for the records where this field exist, and separate group with "unknown city" where field is absent. Or feel free to provide your own way to group data, it's up to you. All fields in "elastic_data.json" are mandatory except of "geoip.region_name" and "geoip.city_name". Your solution must be uploaded to github.
