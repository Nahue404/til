# STRING_AGG

Join values from several rows into one string, available since SQL Server 2017.

```sql
SELECT course_id, STRING_AGG(student_name, ', ') AS students
FROM enrollments
GROUP BY course_id;
```
