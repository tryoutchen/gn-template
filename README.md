This is an example directory structure that compiles some simple targets using
gcc. It is intended to show how to set up a simple GN build.

Don't miss the ".gn" file in this directory!

## Build
 * Mac OS X 10.12.6
   $ ./buildtools/mac/gn gen out/foo
   $ ./buildtools/mac/ninja -C out/foo/ hello

## Run
 * Mac OS X 10.12.6
   $ DYLD_FALLBACK_LIBRARY_PATH=out/foo/obj/ ./out/foo/hello
