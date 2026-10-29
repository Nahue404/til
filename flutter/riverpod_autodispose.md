# autoDispose in Riverpod

Providers without `autoDispose` keep their state forever. Add it to providers tied to a single screen so they are cleaned up when the screen is closed.
