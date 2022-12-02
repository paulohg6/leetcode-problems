

# Problem 
[combine-two-tables](https://leetcode.com/problems/combine-two-tables/)

# Solução
```sql
select distinct Person.firstName,Person.LastName,Address.city,Address.state
from Person left join Address on Person.personId = Address.personId 

;

```
## O que aprendi nesse exercicio.
Left Join, mas mostrou que ainda preciso estudar muito left join, join e outer join
