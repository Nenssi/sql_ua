---
title: "Как я выбираю данные"
date: 2026-04-25
---

### Мой тестовый запрос

```sql
SELECT name, count(*) 
FROM users 
GROUP BY 1 
HAVING count(*) > 1;