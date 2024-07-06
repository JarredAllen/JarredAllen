<img src="https://github.com/my-badges/my-badges/blob/master/badges/fix-commit/fix-4.png?raw=true" alt="I did 4 sequential fixes." title="I did 4 sequential fixes." width="128">
<strong>I did 4 sequential fixes.</strong>
<br><br>

Commits:

- <a href="https://github.com/JarredAllen/mqtt-async-client-rs/commit/9cc811f68f4a3c9059165aa423c9208bee9e8683">9cc811f</a>: Fix intermittent error message on some connections

The library was logging an error on some messages being sent which
didn't listen for a response packet, so this change avoids that
error being logged.
- <a href="https://github.com/JarredAllen/mqtt-async-client-rs/commit/1c2e8717699742ff59d97dbd9c55d07ac442bc85">1c2e871</a>: Fix compile error if used without features
- <a href="https://github.com/JarredAllen/mqtt-async-client-rs/commit/3ed7b3f92bf6d3dc0545db5a6476bf8b49b150ff">3ed7b3f</a>: Fix issue that slipped into integration test
- <a href="https://github.com/JarredAllen/mqtt-async-client-rs/commit/0731e7cd4dcb8742acb4f1f97a510e4396f86fdc">0731e7c</a>: Fix port being placed in the wrong location


Created by <a href="https://github.com/my-badges/my-badges">My Badges</a>