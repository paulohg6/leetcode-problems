

# Problem 
[not-boring-movies](https://leetcode.com/problems/not-boring-movies/)

```sql
SELECT
     id, movie,description,rating
FROM
    Cinema
WHERE
    id%2 <> 0 and description <> "boring"
    order by rating desc
;
```