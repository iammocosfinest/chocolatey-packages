# <img src="https://cdn.jsdelivr.net/gh/chocolatey-community/chocolatey-packages-template@a29fa0531b6152c89cbad2843f0542102d85f375/icons/putty.png" width="48" height="48"/> [putty.portable](https://chocolatey.org/packages/putty.portable)

PuTTY is a free implementation of Telnet and SSH for Windows and Unix platforms, along with an `xterm` terminal emulator.

## Features

- Unicode support
- Control over the SSH encryption key and protocol version
- Command-line SCP and SFTP clients, called "pscp" and "psftp" respectively
- Control over port forwarding with SSH (local, remote or dynamic port forwarding), including built-in handling of X11 forwarding
- Emulates most xterm, VT102 control sequences, as well as much of ECMA-48 terminal emulation
- IP Version 6 support
- Supports 3DES, AES, Arcfour, Blowfish, DES
- Public-key authentication support
- Support for local serial port connections

## Components

- PuTTY: the Telnet, rlogin, and SSH client itself, which can also connect to a serial port
- PSCP: an SCP client, i.e. command-line secure file copy
- PSFTP: an SFTP client, i.e. general file transfer sessions much like FTP
- PuTTYtel: a Telnet-only client
- Plink: a command-line interface to the PuTTY back ends
- Pageant: an SSH authentication agent for PuTTY, PSCP and Plink
- PuTTYgen: an RSA, DSA, ECDSA and EdDSA key generation utility
- pterm: a standalone terminal emulator

## Notes

- **If the package is out of date please check [Version History](#versionhistory) for the latest submitted version. If you have a question, please ask it in [Chocolatey Community Package Discussions](https://github.com/chocolatey-community/chocolatey-packages/discussions) or raise an issue on the [Chocolatey Community Packages Repository](https://github.com/chocolatey-community/chocolatey-packages/issues) if you have problems with the package. Disqus comments will generally not be responded to.**
- Support for putty 64bit have been added to the package when running chocolatey 0.10.4+, to keep using 32bit version of putty please pass `--x86` when installing/upgrading `putty.install`gi *(64bit installation may fail if 32bit is already installed)*
- Use of PuTTY, PSCP, PSFTP and Plink is illegal in countries where encryption is outlawed.
- We believe it is legal to use PuTTY, PSCP, PSFTP and Plink in England and Wales and in many other countries, but we are not lawyers, and so if in doubt you should seek legal advice before downloading it.
- You may find useful information at [cryptolaw.org](http://www.cryptolaw.org/), which collects information on cryptography laws in many countries, but we can't vouch for its correctness.

![screenshot](https://cdn.rawgit.com/chocolatey/chocolatey-coreteampackages/master/automatic/putty.install/screenshot.png)
