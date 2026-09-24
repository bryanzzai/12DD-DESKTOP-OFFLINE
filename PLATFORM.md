# Windows offline edition

This branch is the Windows target for the shared offline web application.

The offline takeout is built by:

```text
.github/offline/prepare_takeout.py
```

The generated package contains `START-THE-12-DAY-DANCER.cmd` and `server.py`.
Run the CMD launcher from the extracted offline package; it opens the local player at `http://127.0.0.1:8765/index.html`.

Large browser media files are delivered in the offline package, not committed to Git.
