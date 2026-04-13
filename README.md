EpsilonBSD 1.0 - Vulkanic I
======

EpsilonBSD - A fast, secure and functional UNIX-like
4.4BSD Operating System forked from NetBSD.

Building the system
--------

You can cross-build from most UNIX-like operating systems.
To build for amd64 (x86_64), in the src directory:

    ./build.sh -U -u -j4 -m amd64 -O ~/obj release

Additional build information available in the [BUILDING](BUILDING) file.

Testing
-------

On a running EpsilonBSD system:

    cd /usr/tests; atf-run | atf-report
