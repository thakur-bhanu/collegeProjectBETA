# python


H1 Python


A streaming video company, Codeflix, needs your help analyzing their user data. We’ve imported a portion of their dataset into the SQL workspace for this lesson.

>1. Use COUNT() and a LIKE operator to determine the number of users that have an email ending in ‘.com’.


SELECT COUNT(*)
FROM users
WHERE email LIKE '%.com'
