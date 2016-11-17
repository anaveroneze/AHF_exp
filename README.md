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
-Arquivo: LCDM.128.z50.ascii Tamanho: 109185665 Execuções: 5
- (1) Tempo Exec: .765706462		Nº threads: 1
- (2) Tempo Exec: .747518179		Nº threads: 1
- (3) Tempo Exec: .745798842		Nº threads: 1
- (4) Tempo Exec: .745921961		Nº threads: 1
- (5) Tempo Exec: .746073438		Nº threads: 1
- (1) Tempo Exec: .685684287		Nº threads: 2
- (2) Tempo Exec: .682689105		Nº threads: 2
- (3) Tempo Exec: .680448586		Nº threads: 2
- (4) Tempo Exec: .685162721		Nº threads: 2
- (5) Tempo Exec: .691178322		Nº threads: 2
- (1) Tempo Exec: .620378139		Nº threads: 3
- (2) Tempo Exec: .626848629		Nº threads: 3
- (3) Tempo Exec: .631596703		Nº threads: 3
- (4) Tempo Exec: .627769218		Nº threads: 3
- (5) Tempo Exec: .621896827		Nº threads: 3
- (1) Tempo Exec: .654973621		Nº threads: 4
- (2) Tempo Exec: .648460265		Nº threads: 4
- (3) Tempo Exec: .640325573		Nº threads: 4
- (4) Tempo Exec: .648004519		Nº threads: 4
- (5) Tempo Exec: .642601211		Nº threads: 4
-Arquivo: Hernquist100000_000.txt Tamanho: 11648963 Execuções: 5
- (1) Tempo Exec: 5.044142996		Nº threads: 1
- (2) Tempo Exec: 4.768603999		Nº threads: 1
- (3) Tempo Exec: 4.805396690		Nº threads: 1
- (4) Tempo Exec: 4.772350187		Nº threads: 1
- (5) Tempo Exec: 4.780785538		Nº threads: 1
- (1) Tempo Exec: 4.736382709		Nº threads: 2
- (2) Tempo Exec: 4.702574079		Nº threads: 2
- (3) Tempo Exec: 4.713062013		Nº threads: 2
- (4) Tempo Exec: 4.705608754		Nº threads: 2
- (5) Tempo Exec: 4.718010315		Nº threads: 2
- (1) Tempo Exec: 4.671525273		Nº threads: 3
- (2) Tempo Exec: 4.642063646		Nº threads: 3
- (3) Tempo Exec: 4.677645365		Nº threads: 3
- (4) Tempo Exec: 4.651407175		Nº threads: 3
- (5) Tempo Exec: 4.694306306		Nº threads: 3
- (1) Tempo Exec: 4.703493680		Nº threads: 4
- (2) Tempo Exec: 4.686275875		Nº threads: 4
- (3) Tempo Exec: 4.671572457		Nº threads: 4
- (4) Tempo Exec: 4.684032832		Nº threads: 4
- (5) Tempo Exec: 4.687207867		Nº threads: 4
-Arquivo: LCDM.064.z25.ascii Tamanho: 12282038 Execuções: 5
- (1) Tempo Exec: .242461992		Nº threads: 1
- (2) Tempo Exec: .241731998		Nº threads: 1
- (3) Tempo Exec: .241426917		Nº threads: 1
- (4) Tempo Exec: .242318040		Nº threads: 1
- (5) Tempo Exec: .240607836		Nº threads: 1
- (1) Tempo Exec: .178951021		Nº threads: 2
- (2) Tempo Exec: .175399361		Nº threads: 2
- (3) Tempo Exec: .174681143		Nº threads: 2
- (4) Tempo Exec: .175680250		Nº threads: 2
- (5) Tempo Exec: .183803847		Nº threads: 2
- (1) Tempo Exec: 44.681356228		Nº threads: 3
- (2) Tempo Exec: 32.374489218		Nº threads: 3
- (3) Tempo Exec: 59.129208501		Nº threads: 3
- (4) Tempo Exec: 77.677651733		Nº threads: 3
- (5) Tempo Exec: 19.722413685		Nº threads: 3
- (1) Tempo Exec: 75.227463800		Nº threads: 4
- (2) Tempo Exec: 54.959492892		Nº threads: 4
- (3) Tempo Exec: 17.328829041		Nº threads: 4
- (4) Tempo Exec: 35.686743624		Nº threads: 4
- (5) Tempo Exec: 34.273076732		Nº threads: 4
-Arquivo: LCDM.z31.ascii Tamanho: 235428 Execuções: 5
- (1) Tempo Exec: .264564872		Nº threads: 1
- (2) Tempo Exec: .269319672		Nº threads: 1
- (3) Tempo Exec: .262593112		Nº threads: 1
- (4) Tempo Exec: .240744095		Nº threads: 1
- (5) Tempo Exec: .242071168		Nº threads: 1
- (1) Tempo Exec: .172865161		Nº threads: 2
- (2) Tempo Exec: .174375083		Nº threads: 2
- (3) Tempo Exec: .174017715		Nº threads: 2
- (4) Tempo Exec: .174738487		Nº threads: 2
- (5) Tempo Exec: .175196114		Nº threads: 2
- (1) Tempo Exec: 17.455834847		Nº threads: 3
- (2) Tempo Exec: 37.953328454		Nº threads: 3
- (3) Tempo Exec: 18.104131378		Nº threads: 3
- (4) Tempo Exec: 38.932474395		Nº threads: 3
- (5) Tempo Exec: 65.135592284		Nº threads: 3
- (1) Tempo Exec: 69.979038393		Nº threads: 4
- (2) Tempo Exec: 81.035622500		Nº threads: 4
- (3) Tempo Exec: 32.183654872		Nº threads: 4
- (4) Tempo Exec: 45.524305963		Nº threads: 4
- (5) Tempo Exec: 30.940065832		Nº threads: 4
