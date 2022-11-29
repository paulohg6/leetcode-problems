

# Problem 
[group-sold-products-by-the-date](https://leetcode.com/problems/group-sold-products-by-the-date/)

# Solução
```sql
select sell_date, count(distinct product) as num_sold,
group_concat(distinct product order by product asc) as products
from Activities
group by sell_date
order by sell_date
;

```
## O que aprendi nesse exercicio.
Não sabia a respeito da função group_concat que concatena conforme as regras passadas pra ela.
