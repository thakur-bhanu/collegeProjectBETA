# python


H1 Python


A streaming video company, `Codeflix` , needs your help analyzing their user data.

***

>_1. Determine the number of users that have an email ending in ‘.com’._
``` SQL
SELECT COUNT(*)
FROM users
WHERE email LIKE '%.com'
```

***

>_2. What are the most popular first names on Codeflix?_
``` SQL
SELECT first_name, COUNT(*) AS count
FROM users
GROUP BY 1
ORDER BY 2 DESC
LIMIT 10;
```
***

>_1. Determine the number of users that have an email ending in ‘.com’._
``` SQL
SELECT COUNT(*)
FROM users
WHERE email LIKE '%.com'
```

***

>_2. What are the most popular first names on Codeflix?_
``` SQL
SELECT first_name, COUNT(*) AS count
FROM users
GROUP BY 1
ORDER BY 2 DESC
LIMIT 10;
```

***

>_1. Determine the number of users that have an email ending in ‘.com’._
``` SQL
SELECT COUNT(*)
FROM users
WHERE email LIKE '%.com'
```

***

>_2. What are the most popular first names on Codeflix?_
``` SQL
SELECT first_name, COUNT(*) AS count
FROM users
GROUP BY 1
ORDER BY 2 DESC
LIMIT 10;
```
