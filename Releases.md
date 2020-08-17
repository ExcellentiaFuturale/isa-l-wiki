## ISA-L Crypto v2.23 (Planned for 2H’20)
* AES-GCM, AES-XTS for next gen CPU

## ISA-L v2.29 (Released February 2020)
* EC performance improvements for 6+ parity
* CRC32 and CRC16 next gen CPU

## ISA-L v2.28 (Released October 2019)
* CRC performance improvements for next gen CPU

## ISA-L Crypto v2.22 (Released August 2019)
* Multi-buffer SM3 functions. Experimental base functions only.
* Multi-architecture support

## ISA-L v2.27 (Released June 2019)
* Threaded igzip

## v2.26 (Released March 2019)
* Adler32 function
* Multi-arch improvements
* Performance test improvements
* Various fixes for sanitizer warnings

## v2.25 (Released December 2018)
* Compression on random file performance improvements
* Additional small file compression improvements
* Multi-arch autoconf

## v2.24 (Released September 2018)
* Small file compression performance improvements
* igzip gzip/zlib header/trailer handling
* igzip userspace tool/example
* Zero detect memory function

## v2.23 (Released June 2018)
* Decompression Performance Improvements (Multi Byte Decode)

## v2.22 (Released March 2018)
* Level 3 Compression performance improvements
* Better EC Examples

## v2.21 (Released December 2017)
* Level 2 & 3 Compression Level added. Level 3 is currently only optimized for processors with AVX512 instructions.
* New T10dif CRC and Copy function 
* CRC32 iSCSI performance improvements 
* Multi-buffer hash performance improvement for Intel Atom processors.
* New base functions for multi-buffer hashes.

## v2.20 (Released September 2017)
* Multi Buffer Hashing : extend the max size to > 4 GB 
* Add Non Temporal(NT) runtime versions of AES_GCM
* Add Saturation Benchmark for determining the saturation point for each algorithm like MBH, CRC, AES and EC.   

## v2.19 (Released June 2017)
* Rolling Hash
* Multi Buffer Hash improvements 
* AES GCM : super small packet performance improvements 
* Adler and zlib format for Inflate\Deflate 

## v2.18 ( Released March 2017)
* New 2-pass fully-dynamic deflate compression (level 0-1). 
* Base functions for multi-architecture support
* Multi-hash SHA-256 based
* RAID AVX512 versions

## v2.17 ( Released December 2016)
ISA-L v2.17 features summary 
* Fast Decompression (Inflate) - New.
* Compression Improvements (Deflate) - speed, compression ratio improvements and new features.
* Fast Custom Huffman Code generation – creates optimized Huffman table based on some sample input.
* CRC64
