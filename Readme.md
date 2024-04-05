
# Minium - the bare minimum

Need store lots of data? Too big for loading in one file and writing back after?

You need a folder with many files in some particular schema. You also need library for interacting.

Don't want to write library? Here is library. Library comes with basic schema. You worry about structure.

Objects are stored, indexed by checksum, reference counted for garbage collection.

Objects are bytestrings. 100 bytes? Go for it! 1 GB? Go for it. 0 bytes? Why not!

Be careful. Objects are reference counted. Don't create cyclic references.

![GitHub commit activity](https://img.shields.io/github/commit-activity/m/esdevver/minium)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)

## Runner up taglines

Minium: it's on your computer. \
Minium: it's *actually* lightweight. \
Minium: this ain't your grandma's embedded CAS.
