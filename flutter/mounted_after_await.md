# Check mounted after await

After an `await`, the widget may be gone. Check `if (!context.mounted) return;` before using the context to navigate or show a snackbar.
