# Weather Obeservation Station 7

Query the list of CITY names ending with vowels (a, e, i, o, u) from STATION. Your result cannot contain duplicates.

**Input Format**

The STATION table is described as follows:

<img src="https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg" title="Station.jpg">

where LAT_N is the northern latitude and LONG_W is the western longitude.

# Solution
``` sql
SELECT
    DISTINCT  CITY 
FROM 
    STATION 
WHERE 
    CITY LIKE '%a' 
OR
    CITY LIKE '%e'
OR
    CITY LIKE '%i'
OR
    CITY LIKE '%o'
OR
    CITY LIKE '%u';
```
