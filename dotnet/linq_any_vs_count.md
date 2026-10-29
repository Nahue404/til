# Any() instead of Count() > 0

`Any()` stops at the first match, `Count()` walks the whole sequence. With EF Core, `Any()` translates to `EXISTS`, which is cheaper.
