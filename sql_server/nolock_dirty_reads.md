# NOLOCK reads dirty data

`WITH (NOLOCK)` can return rows that are later rolled back, or read the same row twice during a page split. Use `READ COMMITTED SNAPSHOT` if blocking is the real problem.
