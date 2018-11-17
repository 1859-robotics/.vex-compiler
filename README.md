# .vex-compiler
compiles a folder to a .vex file because the current VCS kinda really sucks...

That and atom is fucking amazing

# Install:
```
git clone yada yada yada...
npm install
npm start
```
----

.env stuff:

Recomended
```
WATCH_DIR=./src
BUILD_DIR=./
ENTRY_POINT=./src/main.cpp
```
WATCH_DIR: the path to be watched (relative to index.js)
BUILD_DIR: the path to produce the .vex file (relative to index.js)
ENTRY_POINT: the first file loaded

----
# documentation

use:
```
#paste "./path/to/file.cpp"
```
in order to add the file relative to the current file to the main file... (wow that sounded way less confusing in my head)
it is very literally just copy/paste, you do not need header files. This may happen later but i am lazy and making this a mere 9 hours before i need it so you get this for now.
