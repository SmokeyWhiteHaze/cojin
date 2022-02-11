cojin
=============

Setup
---------------------
cojin is experimental cojin client and it builds the backbone of the network. However, it downloads and stores the entire history of cojin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.


Running
---------------------
The following are some helpful notes on how to run cojin on your native platform.

### Unix

Unpack the files into a directory and run:

- /usr/local/bin/cojin-qt (GUI) or
- /usr/local/bin/cojind (headless)

### Windows

Unpack the files into a directory, and then run cojin-qt.exe.

### OS X

Drag cojin to your applications folder, and then run cojin
Building
---------------------
The following are developer notes on how to build cojin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

