## Language Bindings

* [Python](https://www.python.org)
  - [python-isal](https://github.com/pycompression/python-isal) Re-implementation
    of the zlib and gzip modules using isa-l as a back-end for faster
    decompression and compression.
* [Java](https://www.oracle.com/java/)
  - [Genomics Kernel Library](https://github.com/Intel-HLS/GKL) Optimized
    versions of compute kernels as used in genomics applications like
    [GATK](https://github.com/broadinstitute/gatk) and
    [HTSJDK](https://github.com/samtools/htsjdk). Includes a deflater and
    inflater that use the ISA-L library.
* [Go](https://go.dev/)
  - [ISALgo](https://github.com/intel/ISALgo) This ISA-L wrapper allows Go applications
    to make use of the optimized low-level functions provided by the Intel(R) ISA-L library 
    including gzip, compression and decompression.