**Cache Memory**

| Parameters                  | Level 1 (L1)         | Level 2 (L2)                                     | Level 3 (L3)                                                                                               | Level 4 (L4)                    |
|-----------------------------|----------------------|--------------------------------------------------|------------------------------------------------------------------------------------------------------------|---------------------------------|
| Built                       | Into CPU             | Resides into separate chip next to the CPU.      | CPUs having both L1 and L2 cache built-in and designate separate cache chip as L3.                         | Aka DRAM buffer.                |
| Speed                       | Fastest and smallest | Still faster than RAM                            |                                                                                                            |                                 |
| Instruction and Data caches | Upto 64 KB per core. | Upto 512 KB per core (or shared upto two cores). | Vary from 8MB to 32MB (shared across all cores or sliced to multiple instances to be associated per core.) | Additional cache size of 128 MB |
| Data delivery latency       |                      | 5 to 10 CPU cycles                               | 10 to 20 CPU cycles                                                                                        |                                 |
