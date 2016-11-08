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
-Arquivo: LCDM.128.z50.ascii Tamanho: 109185665 Execuções: 5
-1 Tempo Exec: total time          =        1 seconds (0.000278 hours)
-2 Tempo Exec: total time          =        1 seconds (0.000278 hours)
-3 Tempo Exec: total time          =        0 seconds (       0 hours)
-4 Tempo Exec: total time          =        1 seconds (0.000278 hours)
-5 Tempo Exec: total time          =        1 seconds (0.000278 hours)
-Arquivo: Hernquist100000_000.txt Tamanho: 11648963 Execuções: 5
-1 Tempo Exec: total time          =        3 seconds (0.000833 hours)
-2 Tempo Exec: total time          =        3 seconds (0.000833 hours)
-3 Tempo Exec: total time          =        3 seconds (0.000833 hours)
-4 Tempo Exec: total time          =        3 seconds (0.000833 hours)
-5 Tempo Exec: total time          =        3 seconds (0.000833 hours)
-Arquivo: LCDM.064.z25.ascii Tamanho: 12282038 Execuções: 5
-1 Tempo Exec: total time          =       39 seconds (  0.0108 hours)
-2 Tempo Exec: total time          =       68 seconds (  0.0189 hours)
-3 Tempo Exec: total time          =       62 seconds (  0.0172 hours)
-4 Tempo Exec: total time          =       41 seconds (  0.0114 hours)
-5 Tempo Exec: total time          =       17 seconds ( 0.00472 hours)
-Arquivo: LCDM.z31.ascii Tamanho: 235428 Execuções: 5
-1 Tempo Exec: total time          =       43 seconds (  0.0119 hours)
-2 Tempo Exec: total time          =       53 seconds (  0.0147 hours)
-3 Tempo Exec: total time          =       16 seconds ( 0.00444 hours)
-4 Tempo Exec: total time          =       30 seconds ( 0.00833 hours)
-5 Tempo Exec: total time          =       32 seconds ( 0.00889 hours)
```
###Snapshot
```
-Arquivo: LCDM.128.z50_snapshot Tamanho: 151188208 Execuções: 1 Tempo Exec: total time = 68 seconds (  0.0189 hours)
-Arquivo: LCDM.064.z25_snapshot Tamanho: 151188208 Execuções: 1 Tempo Exec: total time = 70 seconds (  0.0194 hours)
-Arquivo: LCDM.z30_snapshot Tamanho: 151188208 Execuções: 1 Tempo Exec: total time = 70 seconds (  0.0194 hours)
-Arquivo: LCONE.z30_snapshot Tamanho: 151188208 Execuções: 1 Tempo Exec: total time = 93 seconds (  0.0258 hours)
-Arquivo: Hernquist100000_000_snapshot Tamanho: 3600304 Execuções: 1 Tempo Exec: total time = 71 seconds (  0.0197 hours)```
