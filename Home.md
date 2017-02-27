# ISA-L Wiki

## Ports/Repos
* FreeBSD [ports](http://www.freshports.org/devel/isa-l/)
    - To install the port: `cd /usr/ports/devel/isa-l/ && make install clean`
    - To add the package: `pkg install isa-l`
* [Clear Linux](https://clearlinux.org)
    - bundles: user-basic-dev, os-clr-on-clr-dev
* [Debian] (https://www.debian.org)
    - sid/unstable -
      [libisal2](https://packages.debian.org/sid/libisal2),
      [libisal-dev](https://packages.debian.org/sid/libisal-dev)
    - stretch/testing -
      [libisal2](https://packages.debian.org/stretch/libisal2)
      [libisal-dev](https://packages.debian.org/stretch/libisal-dev)
    - stable-backports -
      [libisal2](https://packages.debian.org/stable-backports/libisal2),
      [libisal-dev](https://packages.debian.org/stable-backports/libisal-dev)
* [Ubuntu] (http://packages.ubuntu.com)
    - To install: `sudo apt-get install libisal-dev`
    - yakkety/16.10 - uses ISA-L 2.16.0 - 
      [libisal2](http://packages.ubuntu.com/yakkety/libisal2),
      [libisal-dev](http://packages.ubuntu.com/yakkety/libisal-dev)
    - zesty - uses ISA-L 2.17.0 -
      [libisal2](http://packages.ubuntu.com/zesty/libisal2),
      [libisal-dev](http://packages.ubuntu.com/zesty/libisal-dev)

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
