
# Export to WKT

Write all node, way, and area geometries out in WKT format.


## Prerequisites

You'll need [Libosmium](http://osmcode.org/libosmium) and its dependencies
installed first.


## Building

Osmium-contrib uses CMake for its builds. For Unix/Linux systems a simple
Makefile wrapper is provided to make the build even easier.

To build just type `make`. Results will be in the `build` subdirectory.

Or you can go the long route explicitly calling CMake as follows:

    mkdir build
    cd build
    cmake ..
    make


## Running

Run the program with an OSM file as its only argument:

    export_to_wkt berlin.osm.pbf


## Tests

Run `ctest` after building to run the tests.


## License

This program is released into the Public Domain.


## Author

Jochen Topf (https://jochentopf.com/)

