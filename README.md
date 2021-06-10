# Helidon webserver ssb

This repo contains a minimized version of helidon-webserver 2.3.0.

The current version of helidon-webserver contains a bug in BareResponseImpl.java which will cause ´outOfMemoryError´ in sending large files in http.

ChangeLog:

 . remove some test accordingly.

 . remove other unnecessary project.

 . Fix the memory leak in BareResponseIml.java