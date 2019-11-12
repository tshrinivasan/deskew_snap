This is the snap package for the tool "deskew"

deskew is wonderful command line tool which can fix the skewed scanned images.

https://galfar.vevb.net/wp/projects/deskew/

https://github.com/galfar/deskew

This is a command line tool, available as binary for linux. made with object pascal.
GUI also available.

This is to make deskew as easy installable as ubuntu package or snap.


==What I did

1. downloaded deskew source file from https://galfar.vevb.net/wp/projects/deskew/ ( it has the binary too )
2. Extract the binary alone from /Bin folder inside the downloaded zip file
3. created new tar file as deskew-1.30.tar.gz
4. mentioned this file in snapcraft.yaml
5. Build and released as snap as mentioned in https://snapcraft.io/docs/t/pre-built-apps/6739

