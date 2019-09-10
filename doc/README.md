Veles Core
=============

Setup
---------------------
Veles Core is the official Veles client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Veles transactions, which requires a few hundred gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Veles Core, visit [veles.network](https://veles.network/download.en.html).

Running
---------------------
The following are some helpful notes on how to run Veles Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/veles-qt` (GUI) or
- `bin/velesd` (headless)

### Windows

Unpack the files into a directory, and then run veles-qt.exe.

### macOS

Drag Veles Core to your applications folder, and then run Veles Core.

### Need Help?

* See the documentation at the [Veles Core Wiki](https://github.com/velescore/veles/wiki)
for help and more information.
* Ask for help on the [Veles Core Discord]([https://discord.gg/rXgH6Qn](https://discord.gg/rXgH6Qn)) server.
* Ask for help on the [Veles Core Telegram](https://web.telegram.org/#/im?p=@Velescore) channel.

Building
---------------------
The following are developer notes on how to build Veles Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide (External Link)](https://github.com/veles-core/docs/blob/master/gitian-building.md)

Development
---------------------
The Veles repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/veles/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [Development & Technical Discussion board](https://bitcointalk.org/index.php?board=6.0).
* Discuss project-specific development on #veles-core-dev on Freenode. If you don't have an IRC client, use [webchat here](http://webchat.freenode.net/?channels=veles-core-dev).
* Discuss general Veles development on #veles-dev on Freenode. If you don't have an IRC client, use [webchat here](http://webchat.freenode.net/?channels=veles-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [veles.conf Configuration File](veles-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
