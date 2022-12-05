

# Problem 
[customers-who-never-order](https://leetcode.com/problems/customers-who-never-order/)

```sql
SELECT c.Name as Customers
FROM Customers c
WHERE c.id not in (
SELECT o.CustomerId FROM Orders o
);
```