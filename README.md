# Non-Volatile Memory Related System

Copyright (C) 2015 Yizhou Shan <shanyizhou@ict.ac.cn>

It is a NVM simulator. We do NOT have any chance to modify microcode of Intel.
Hence using Intel PMU to simulate NVM latency seems a feasible solution. This
simulator simulate the write and read latency of NVM, about 105ns and 65ns,
repectively. The bandwidth is simulated by using a transaction threshold of
IMC(Xeon E5 v2 or above has this feature).

For more information about NVM simulator, please read the PMFS paper and a MSST
paper: A study of application performance with Non-Volatile Main memory.
