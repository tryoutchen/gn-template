This is an example directory structure that compiles some simple targets using
gcc. It is intended to show how to set up a simple GN build.

Don't miss the ".gn" file in this directory!

## Build
 * Ubuntu 16.04.3 LTS
   * ./buildtools/linux64/gn gen out/linux64
   * ./buildtools/linux64/ninja -C out/linux64/
 * Mac OS X 10.12.6
   * ./buildtools/mac/gn gen out/mac
   * ./buildtools/mac/ninja -C out/mac/

## Run
 * Ubuntu 16.04.3 LTS
   * ./out/linux64/hello
 * Mac OS X 10.12.6
   * DYLD_FALLBACK_LIBRARY_PATH=out/mac/ ./out/mac/hello
