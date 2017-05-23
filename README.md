# Various stuff

## Bitcoin Core with SegWit UASF BIP148 Patch: Binaries, Source, FAQs, Install How-To

### Source & Binaries for Linux and Windows

* Releases: https://github.com/UASF/bitcoin/releases/
  * Ubuntu PPA: https://launchpad.net/~luke-jr/+archive/ubuntu/bitcoin-core-bip148-unofficial-builds
* Source code: https://github.com/UASF/bitcoin/releases

### How to Install

If you're not an experienced Bitcoin user, you do **not have to use** UASF-specific install and configuration guides guides. 

UASF BIP148 is just a slightly different Bitcoin Core - so all Bitcoin Core 0.14 install guides apply to the UASF BIP148 version. Use whatever Bitcoin Core 0.14 instructions you find easy to follow.

Here's what you need to do:

#### Existing Bitcoin Core users

1. Stop Bitcoin Core
2. Make a secure backup copy of your wallet.dat
3. Remove (uninstall) Bitcoin Core
4. Install a UASF version from Releases (see the link above)

If you're upgrading (for example from Bitcoin Core 0.13 to Bitcoin Core UASF BIP148 0.14.1), follow regular instructions for upgrading from 0.13 to 0.14. Again, there's nothing different in terms of installation for Bitcoin Core UASF BIP148.

#### New User: You don't have existing Bitcoin Core

1. Get the right copy for your OS
2. Follow normal Bitcoin Core instructions & how-to's

**NOTE ABOUT TAR.GZ ARCHIVES**: UASF BIP148 binaries for Windows are installed the same way (double-click). Linux and UNIX users need to decompress downlaoded archive (`tar xfzv bitcoin-0.14.1-bip148_segwit0.3-arm-linux-gnueabihf.tar.gz`, for example) and then navigate to decompressed directory (`cd bitcoin-0.14.1/bin/`) where you can execute bitcoind (`./bitcoind`). Again, this is the standard way to install pre-built binaries - you can refer to Bitcoin Core documentation and online how-to's - there's nothing UASF-specific in here! The configuration file can be in the usual place (`$HOME/.bitcoin/bitcoin.conf`) - refer to official Bitcoin Core 0.14.1 documentation!

Which binary to fetch?

* Raspberry Pi 2 - arm-linux-gnueabihf.tar.gz
* Windows - use the 32-bit installer executable, regardless of your OS (32-bit uses slightly less RAM)

### Other Information

* FAQs: http://www.uasf.co/
* Slack: Bitcoin Core Slack, #uasf channel
* /r/Bitcoin Subreddit Discussion: https://duckduckgo.com/?q=site%3Areddit.com+%22%2Fr%2Fbitcoin%22+uasf

