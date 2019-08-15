Veles Core version 0.18.1 "Blockchain Barracuda" is now available from:

Download: <https://www.veles.network/download.en.html>

This is a new major version release, including new features, various bug
fixes and performance improvements, as well as updated translations.

Please report bugs using the issue tracker at GitHub:

  <https://github.com/velescore/veles/issues>

How to Upgrade
==============

If you are running an older version, shut it down. Wait until it has
completely shut down (which might take a few minutes for older
versions), then run the installer (on Windows) or just copy over
`/Applications/Veles-Qt` (on Mac) or `velesd`/`veles-qt` (on
Linux).

Compatibility
==============

Veles Core is supported and extensively tested on operating systems
using the Linux kernel, macOS 10.10+, and Windows 7 and newer. It is not
recommended to use Veles Core on unsupported systems.

Veles Core should also work on most other Unix-like systems but is not
as frequently tested on them.

In addition to previously-supported CPU platforms, this release's
pre-compiled distribution also provides binaries for the RISC-V
platform.

If you are using the `systemd` unit configuration file located at
`contrib/init/velesd.service`, it has been changed to use
`/var/lib/velesd` as the data directory instead of
`~veles/.veles`. When switching over to the new configuration file,
please make sure that the filesystem on which `/var/lib/velesd` will
exist has enough space (check using `df -h /var/lib/velesd`), and
optionally copy over your existing data directory. See the [systemd init
file section](#systemd-init-file) for more details.

Masternodes
===========
Lowering Masternode collateral from 2000 VLS to 500 VLS . Old Masternode collateral will be valid until block 240000 (circa 2 months from release), until then it is inevitable update your wallet and remake Masternodes , because old one will be not valid anymore and your wallets will generate ivalid votes.

Credits
=======

Thanks to everyone who contributed to this release:

Veles Core contributors
- Uhliksk
- AltcoinBaggins
- Mdfkbtc
