# SQL_Queries

// Returning Cities with a Population higher than 100000 in the USA from a Database // 

SELECT *
FROM CITY
WHERE COUNTRYCODE = 'USA'
AND POPULATION > 100000
