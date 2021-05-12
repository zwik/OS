# Cross compiler
Based on https://wiki.osdev.org/Main_Page
To build the image run `docker build buildenv -t buildenv`.

To start the container you can run `docker run --rm -it -v "${pwd}:/root/env" buildenv`.