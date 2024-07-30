# HackerRanksqlsolution
1. Revising the Select Query I | Easy | HackerRank
Query all columns for all American cities in the CITY table with populations larger than 100000. The CountryCode for America is USA.

The CITY table is described as follows:


Solution
sql

SELECT * FROM CITY
WHERE COUNTRYCODE='USA' AND POPULATION > 100000;
2. Revising the Select Query II | Easy | HackerRank
Query the NAME field for all American cities in the CITY table with populations larger than 120000. The CountryCode for America is USA.

The CITY table is described as follows:


Solution
sql

SELECT NAME FROM CITY
WHERE COUNTRYCODE ='USA' AND POPULATION > 120000;
3. Select All | Easy | HackerRank
Query all columns (attributes) for every row in the CITY table.

The CITY table is described as follows:

