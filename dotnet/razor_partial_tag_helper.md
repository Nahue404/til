# Partial tag helper in Razor

Prefer `<partial name="_Grades" model="Model.Grades" />` over `@Html.Partial`. It is async and does not block the thread.
