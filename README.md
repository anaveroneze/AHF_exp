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

##Running Tests:
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
###Ascii
####1 Execução
```
-Arquivo: LCDM.128.z50.ascii Nº Partículas: 2097152 Tamanho: 109185443 Execuções: 1
- (1) Tempo Exec: real	0m0.823s		Nº threads: 1
- (1) Tempo Exec: real	0m0.699s		Nº threads: 2
- (1) Tempo Exec: real	0m0.697s		Nº threads: 3
- (1) Tempo Exec: real	0m0.730s		Nº threads: 4
-Arquivo: Hernquist100000_000.txt Nº Partículas: 100000 Tamanho: 11648963 Execuções: 1
- (1) Tempo Exec: real	0m5.407s		Nº threads: 1
- (1) Tempo Exec: real	0m5.529s		Nº threads: 2
- (1) Tempo Exec: real	0m5.306s		Nº threads: 3
- (1) Tempo Exec: real	0m5.067s		Nº threads: 4
-Arquivo: LCDM.064.z25.ascii Nº Partículas: 262144 Tamanho: 12281828 Execuções: 1
- (1) Tempo Exec: real	0m0.264s		Nº threads: 1
- (1) Tempo Exec: real	0m0.175s		Nº threads: 2
- (1) Tempo Exec: real	1m48.277s		Nº threads: 3
- (1) Tempo Exec: real	1m47.851s		Nº threads: 4
-Arquivo: LCDM.z31.ascii Nº Partículas: 4096 Tamanho: 235226 Execuções: 1
- (1) Tempo Exec: real	0m0.465s		Nº threads: 1
- (1) Tempo Exec: real	0m0.177s		Nº threads: 2
- (1) Tempo Exec: real	1m32.106s		Nº threads: 3
- (1) Tempo Exec: real	0m58.747s		Nº threads: 4
```
####2 Execuções
```
-Arquivo: LCDM.128.z50.ascii Nº Partículas: 2097152 Tamanho: 109185443 Execuções: 2
- (1) Tempo Exec: real	0m0.782s		Nº threads: 1
- (2) Tempo Exec: real	0m0.803s		Nº threads: 1
- (1) Tempo Exec: real	0m0.712s		Nº threads: 2
- (2) Tempo Exec: real	0m0.723s		Nº threads: 2
- (1) Tempo Exec: real	0m0.778s		Nº threads: 3
- (2) Tempo Exec: real	0m0.778s		Nº threads: 3
- (1) Tempo Exec: real	0m0.828s		Nº threads: 4
- (2) Tempo Exec: real	0m0.728s		Nº threads: 4
-Arquivo: Hernquist100000_000.txt Nº Partículas: 100000 Tamanho: 11648963 Execuções: 2
- (1) Tempo Exec: real	0m5.426s		Nº threads: 1
- (2) Tempo Exec: real	0m5.255s		Nº threads: 1
- (1) Tempo Exec: real	0m4.863s		Nº threads: 2
- (2) Tempo Exec: real	0m4.802s		Nº threads: 2
- (1) Tempo Exec: real	0m4.755s		Nº threads: 3
- (2) Tempo Exec: real	0m4.766s		Nº threads: 3
- (1) Tempo Exec: real	0m4.788s		Nº threads: 4
- (2) Tempo Exec: real	0m4.818s		Nº threads: 4
-Arquivo: LCDM.064.z25.ascii Nº Partículas: 262144 Tamanho: 12281828 Execuções: 2
- (1) Tempo Exec: real	0m0.444s		Nº threads: 1
- (2) Tempo Exec: real	0m0.243s		Nº threads: 1
- (1) Tempo Exec: real	0m0.216s		Nº threads: 2
- (2) Tempo Exec: real	0m0.177s		Nº threads: 2
- (1) Tempo Exec: real	1m1.527s		Nº threads: 3
- (2) Tempo Exec: real	1m16.662s		Nº threads: 3
- (1) Tempo Exec: real	1m0.009s		Nº threads: 4
- (2) Tempo Exec: real	0m53.712s		Nº threads: 4
-Arquivo: LCDM.z31.ascii Nº Partículas: 4096 Tamanho: 235226 Execuções: 2
- (1) Tempo Exec: real	0m0.284s		Nº threads: 1
- (2) Tempo Exec: real	0m0.242s		Nº threads: 1
- (1) Tempo Exec: real	0m0.183s		Nº threads: 2
- (2) Tempo Exec: real	0m0.224s		Nº threads: 2
- (1) Tempo Exec: real	0m34.637s		Nº threads: 3
- (2) Tempo Exec: real	1m34.793s		Nº threads: 3
- (1) Tempo Exec: real	0m27.874s		Nº threads: 4
- (2) Tempo Exec: real	1m23.538s		Nº threads: 4
```
##Running Tests:
``` <code>
Arquitetura:           x86_64
Modo(s) operacional da CPU:32-bit, 64-bit
Ordem dos bytes:       Little Endian
CPU(s):                8
Lista de CPU(s) on-line:0-7
Thread(s) per núcleo  2
Núcleo(s) por soquete:4
Soquete(s):            1
Nó(s) de NUMA:        1
ID de fornecedor:      GenuineIntel
Família da CPU:       6
Modelo:                44
Nome do modelo:        Intel(R) Xeon(R) CPU           E5620  @ 2.40GHz
Step:                  2
CPU MHz:               1600.000
CPU MHz máx.:         2401,0000
CPU MHz mín.:         1600,0000
BogoMIPS:              4800.14
Virtualização:       VT-x
cache de L1d:          32K
cache de L1i:          32K
cache de L2:           256K
cache de L3:           12288K
CPU(s) de nó0 NUMA:   0-7
```
###Ascii
```
-Arquivo: LCDM.128.z50.ascii Nº Partículas: 2097152 Tamanho: 109185443 Execuções: 1
- (1) Tempo Exec: real	0m1.374s		Nº threads: 1
- (1) Tempo Exec: real	0m1.154s		Nº threads: 2
- (1) Tempo Exec: real	0m34.536s		Nº threads: 3
- (1) Tempo Exec: real	0m41.829s		Nº threads: 4
-Arquivo: Hernquist100000_000.txt Nº Partículas: 100000 Tamanho: 11648963 Execuções: 1
- (1) Tempo Exec: real	0m6.843s		Nº threads: 1
- (1) Tempo Exec: real	0m6.619s		Nº threads: 2
- (1) Tempo Exec: real	0m30.094s		Nº threads: 3
- (1) Tempo Exec: real	1m37.094s		Nº threads: 4
-Arquivo: LCDM.064.z25.ascii Nº Partículas: 262144 Tamanho: 12281828 Execuções: 1
- (1) Tempo Exec: real	0m0.500s		Nº threads: 1
- (1) Tempo Exec: real	0m0.383s		Nº threads: 2
- (1) Tempo Exec: real	0m46.929s		Nº threads: 3
- (1) Tempo Exec: real	0m36.501s		Nº threads: 4
-Arquivo: LCDM.z31.ascii Nº Partículas: 4096 Tamanho: 235226 Execuções: 1
- (1) Tempo Exec: real	0m0.500s		Nº threads: 1
- (1) Tempo Exec: real	0m0.380s		Nº threads: 2
- (1) Tempo Exec: real	0m31.061s		Nº threads: 3
- (1) Tempo Exec: real	1m14.163s		Nº threads: 4
```




