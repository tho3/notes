### Introduction

Maintaining a system always take a lot of work.  One needs to read the documentation and figure out the multiple steps involved.  There are many tools involved.

How to pass parameters to change the install path?
32 and 64 bit location


#### These command are configure related.
autoconf
libtoolize
aclocal
autoheader

#### autoconf
autoconf generates the configuraition file

#### M4
M4 is the macro that used to define the make file and directories.


#### configure
Configure --help

#### cmake
cmake -DLIB_SUFFIX=64 This defines the library should be saved in /usr/local/lib/lib64.  Default is /usr/local
https://stackoverflow.com/questions/6241922/how-to-use-cmake-install-prefix  change the cmake install prefix

#### cross compiling
This lets one to compile software from one platform to another platform.
Many embedded systems had limited memory to host a compiler.  Therefore, their application need to be built on another platform.
See https://en.wikipedia.org/wiki/Cross_compiler for more explanation

make CROSS=x86_64-w64-mingw32-

#### cross compiling examples.
* https://github.com/tpoechtrager/osxcross
* https://smallhacks.wordpress.com/2018/01/08/c-cross-compilation-on-linux-for-the-freebsd-target-using-gcc-or-clang/ for FreeBSD
* https://github.com/phracker/MacOSX-SDKs

### ccache
* https://www.opengeosys.org/docs/devguide/advanced/compiler-cache/
* https://stackoverflow.com/questions/45991561/ccache-basedir-doesnt-work-as-expected
* https://stackoverflow.com/questions/1815688/how-to-use-ccache-with-cmake
