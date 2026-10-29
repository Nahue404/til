# SerializeField on private fields

Use `[SerializeField] private float speed;` instead of a public field. It shows up in the Inspector without exposing it to other scripts.
