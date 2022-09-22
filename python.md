# python


H1 Python


A streaming video company, Codeflix, needs your help analyzing their user data. We’ve imported a portion of their dataset into the SQL workspace for this lesson.

>1. Determine the number of users that have an email ending in ‘.com’.


``` SQL
SELECT COUNT(*)
FROM users
WHERE email LIKE '%.com'
```
>2. What are the most popular first names on Codeflix?


``` SQL
SELECT first_name, COUNT(*) AS count
FROM users
GROUP BY 1
ORDER BY 2 DESC
LIMIT 10;
```

``` SQLSELECT first_name, COUNT(*) AS count
FROM users
GROUP BY 1
ORDER BY 2 DESC
LIMIT 10;
```



``` SQL
SELECT COUNT(*)
FROM users
WHERE email LIKE '%.com'
```



``` SQL
SELECT COUNT(*)
FROM users
WHERE email LIKE '%.com'
```



``` SQL
SELECT COUNT(*)
FROM users
WHERE email LIKE '%.com'
```
