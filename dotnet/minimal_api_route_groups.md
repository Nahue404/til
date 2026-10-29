# Route groups in minimal APIs

Use `MapGroup` to share a prefix and filters between endpoints.

```csharp
var api = app.MapGroup("/api/students").RequireAuthorization();
api.MapGet("/", GetAll);
api.MapGet("/{id:int}", GetById);
```
