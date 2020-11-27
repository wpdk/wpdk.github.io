The Windows Platform Development Kit (WPDK) enables applications based on the Storage Performance Development Kit ([SPDK](http://www.spdk.io)) to build and run as native Windows executables by providing header files and a lightweight library that implement required POSIX/Linux functionality.

The project grew out of work being done by [MayaData](https://mayadata.io/) to build [Mayastor](https://github.com/openebs/mayastor), a high speed Container Attached Storage stack for [OpenEBS](https://openebs.io/).

## Current Status

The project is at an alpha stage:

* All of the SPDK source compiles, apart from spdk_top which requires *libcurses*.
* All of the SPDK Unit Tests pass.
* The iSCSI target can serve storage.
* Unit tests exist for the majority of the WPDK functionality.

## Contributing

Contributions are welcome and needed!

## Getting Started

The code and documentation can be found in the [WPDK Repository](https://github.com/wpdk/wpdk).
