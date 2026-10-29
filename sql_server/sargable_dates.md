# Sargable date filters

Wrapping a column in a function prevents index seeks.

```sql
-- slow
WHERE YEAR(created_at) = 2024
-- fast
WHERE created_at >= '2024-01-01' AND created_at < '2025-01-01'
```
