# OUTPUT clause

Get the inserted ids without a second query.

```sql
INSERT INTO grades (student_id, score)
OUTPUT inserted.id
VALUES (10, 8);
```
