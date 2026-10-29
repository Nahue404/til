# Avoid async void

An `async void` method cannot be awaited and its exceptions crash the process. Return `Task` instead. The only valid case is an event handler.
