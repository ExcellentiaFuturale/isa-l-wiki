# ISA-L Wiki

## Ports/Repos
* FreeBSD - http://www.freshports.org/devel/isa-l/
    - To install the port: cd /usr/ports/devel/isa-l/ && make install clean
    - To add the package: pkg install isa-l
* Clear Linux - https://clearlinux.org/
    - bundles: user-basic-dev, os-clr-on-clr-dev
* Debian (unstable) - https://www.debian.org/releases/sid/
    - https://packages.debian.org/sid/libisal2
    - https://packages.debian.org/sid/libisal-dev

## Release planning 2.18
* Compression ratio improvements
* Base functions for multi-architecture support
* Multi-hash SHA-256 based
* RAID AVX512 versions


## Release 2.17 (December 2016)

ISA-L v2.17 features summary (see release notes for details):
* Fast Decompression (Inflate) - New.
* Compression Improvements (Deflate) - speed, compression ratio improvements and new features.
* Fast Custom Huffman Code generation – creates optimized Huffman table based on some sample input.
* CRC64
