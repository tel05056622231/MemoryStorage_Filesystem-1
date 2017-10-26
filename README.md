# MemoryStorage_Filesystem
Yongseob <tel.05056622231@gmail.com>

# Requirements
- It need's a patched kernel (MemoryStorage_Kernel). 
- NUMA system
- Non-volatile DIMM
- etc.

# How to use
$ make
$ sudo insmod ./r2nvmm.ko
$ sudo mount -t r2nvmm -o size=??g /mnt


## Copyright
Yongseob
