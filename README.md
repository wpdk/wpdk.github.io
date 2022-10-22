The Windows Platform Development Kit (WPDK) enables applications based on the Storage Performance Development Kit ([SPDK](http://www.spdk.io)) to build and run as native Windows executables by providing header files and a lightweight library that implement required POSIX/Linux functionality.

The project grew out of work being done by [DataCore](https://datacore.com/) to build [OpenEBS Mayastor](https://github.com/openebs/mayastor), a high speed Container Attached Storage stack for [OpenEBS](https://openebs.io/).

## Recent News

[DataCore](https://datacore.com) has contributed the Windows Driver Unit Test Framework (WDUTF) to enable the unit testing of Windows kernel drivers. This has been a key tool in DataCore's test and development process for many years.

For more details, see the [WDUTF Repository](https://github.com/wpdk/wdutf) where the code and documentation can be found!

## Current Status

The project is at an alpha stage:

* All of the SPDK source compiles, apart from spdk_top which requires *libcurses*.
* All of the SPDK Unit Tests pass.
* The iSCSI target can serve storage.
* The NVMe over TCP target can serve storage.
* The SPDK stack can attach to a physical NVMe disk and issue I/O.
* Unit tests exist for the majority of the WPDK functionality.

## Getting Started

The code and documentation can be found in the [WPDK Repository](https://github.com/wpdk/wpdk),
together with a [Getting Started](https://github.com/wpdk/wpdk#start) guide.

## Contributing

Contributions are welcome and needed!

Please join the [SPDK community](https://spdk.io/community) and tell us how you are using SPDK on Windows.
For real-time discussions, the SPDK Slack contains a [Windows channel](https://spdk-team.slack.com/archives/C01Q700GPGU).

