# 1

# ORDER BY
Сортирует столюцы по убыванию или возрастанию
По умолчанию возрастание
можно менять с  помощью операторов ASC|DESC
``` SQL
SELECT [АТР.], ...
FROM [ТАБ.]
ORDER BY [АТР. | ПОЗИЦИЯ АТР. В SELECT], ... <ASC | DESC> 
```

# GROUP BY

``` SQL
> Может быть аналогией DISTINCT
SELECT  [АТР.]
FROM [ТАБ.]
GROUP BY [АТР.]
```