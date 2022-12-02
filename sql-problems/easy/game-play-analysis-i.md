

# Problem 
[game-play-analysis-i](https://leetcode.com/problems/game-play-analysis-i/)


# Solução
```sql
select player_id, MIN(event_date)   as first_login 
from Activity
group by player_id
;
```
# O que aprendi nesse exercicio.
Não sabia a respeito da função MIN que traria a menor data do group by

