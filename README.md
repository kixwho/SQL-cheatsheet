<img width="562" height="131" alt="image" src="https://github.com/user-attachments/assets/4fc578e1-64bb-44d2-9589-e80decfcf4db" />

| Operator  | Function | Example |
| ------------- | ------------- | ------------- |
| =  | Equal to  | WHERE school = 'USC'  |
| <> or !=  | Not equal to  | WHERE school <> 'UCLA'  |
| >  | Greater than  | WHERE salary > 20000  |
| <  | Less than  | WHERE salary < 60500  |
| >=  | Greater than or equal to  | WHERE salary >= 20000  |
| <=  | Less than or equal to  | WHERE salary <= 60500  |
| BETWEEN  | Within a range  | WHERE salary BETWEEN 20000 AND 40000  |
| IN  | Match one of a set of values  | WHERE last_name IN ('Bush', 'Roush')  |
| LIKE  | Match a pattern (case sensitive)  | WHERE first_name LIKE 'Sam%'  |
| ILIKE  | Match a pattern (case insensitive)  | WHERE first_name ILIKE 'sam%'  |
| NOT  | Negates a condition  | WHERE first_name NOT ILIKE 'sam%'  |
| \|\|  | CONCAT within the same row  | SELECT name \|\| ' works as a ' \|\| job  |
| ~  | Matches regular expression  | WHERE product_code ~ '^[A-Z]{2}[0-9]{4}$'  |

Need more practical recipes? [SQL Excel translator](https://github.com/kixwho/SQL-Excel-translator)

## Practice resources
[LeetCode SQL 50 study plan](https://leetcode.com/studyplan/top-sql-50/) covers all the essential patterns :)

[Browser-based SQLite playground](https://sqliteviz.com/app/) Drop a data file, start querying in SQL immediately. No installation needed 👍
