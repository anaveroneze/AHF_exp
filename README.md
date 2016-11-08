# AHF_exp
Amiga's Halo Finder learning experience.
http://popia.ft.uam.es/AHF/

How to run: 
$ bin/AHF-v1.0-091 AHF.input 

Data to test: 
http://popia.ft.uam.es/AMIGA/files/Sample.tgz

Conversion ascii <-> gadget2:
https://github.com/martinsparre/Gadget2Conversion

Compilation flags: change in Makefile.config or ../src/define.h

``` <code>
Arquitetura:           x86_64
Modo(s) operacional da CPU:32-bit, 64-bit
Byte Order:            Little Endian
CPU(s):                4
On-line CPU(s) list:   0-3
Thread(s) per núcleo   2
Núcleo(s) por soquete: 2
Soquete(s):            1
Nó(s) de NUMA:         1
ID de fornecedor:      GenuineIntel
Família da CPU:        6
Modelo:                61
Model name:            Intel(R) Core(TM) i5-5200U CPU @ 2.20GHz
Step:                  4
CPU MHz:               2200.000
CPU max MHz:           2700,0000
CPU min MHz:           500,0000
BogoMIPS:              4389.44
Virtualização:         VT-x
cache de L1d:          32K
cache de L1i:          32K
cache de L2:           256K
cache de L3:           3072K
NUMA node0 CPU(s):     0-3
```
##Running Tests:
###Ascii
```
-Arquivo: LCDM.128.z50.ascii Tamanho: 109185665 Execuções: 1 Tempo Exec: total time = 69 seconds (  0.0192 hours)
-Arquivo: Hernquist100000_000.txt Tamanho: 11648963 Execuções: 1 Tempo Exec: total time = 81 seconds (  0.0225 hours)
-Arquivo: LCDM.064.z25.ascii Tamanho: 12282038 Execuções: 1 Tempo Exec: total time = 25 seconds ( 0.00694 hours)
-Arquivo: LCDM.z30.ascii Tamanho: 235428 Execuções: 1 Tempo Exec: total time = 48 seconds (  0.0133 hours)
