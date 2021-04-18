# SQL-Practice
/* This is the practice for SQL
/* Weather Observation Station 8

SELECT DISTINCT CITY FROM STATION WHERE CITY REGEXP '^[AEIOU].*[AEIOU]$' ORDER BY CITY
^[] Represents the previous any of the letters in the bracket
.* Represents any numbers or letters
[]$ Represents any letters at the last in the bracket
