# Borrar-planes-de-ejecuci-n-en-SQL-Server

```sql
-- Borrar todos los planes de memoria cache
DBCC FREEPROCCACHE WITH NO_INFOMSGS

-- Vaciar la cache de datos
DBCC DROPCLEANBUFFERS WITH NO_INFOMSGC
```
