The Windows Platform Development Kit (WPDK) enables applications based on the Storage Performance Development Kit (SPDK) to build and run as native Windows executables by providing header files and a lightweight library that implement required POSIX/Linux functionality.

The project grew out of work being done by MayaData to build Mayastor, a high speed Container Attached Storage stack for OpenEBS.

The scope of the project is limited to supporting the Storage Performance Development Kit. It is not intended to be a generic Linux emulation library like Cygwin. Functionality is mapped as closely as possible to existing Windows semantics with the minimum of emulation.

The code, documentation and current status can be found in the [WPDK Repository](https://github.com/wpdk/wpdk).
