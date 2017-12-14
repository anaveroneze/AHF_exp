## Data used - LCDM: 
https://wwwmpa.mpa-garching.mpg.de/galform/virgo/vls/index.shtml

## Notes: 
* mostly of the time the program use only 1 thread 
* tests made with 3 grids of refinement (3 level halos)
* dVir = -1 virial overdensity criterion (<0: let AHF calculate it)
* http://graphics.cs.ucdavis.edu/~okreylos/Research/AMRVis/ 

## Analysis tools: 

* http://scitools.com/trial-thanks/understand/ 
* Intel VTune

## Analysis

OMP_NUM_THREADS=4

![main](images/Butterfly-main.png?raw=true "Butterfly Graphical View based on main.c")

#### Grid:

Mostly of the time was spent generating the grid: </br>

file: generate_grids.c </br>
![vtune](images/AHFVtune.png?raw=true "vtune")
function: gen_AMRhierarchy</br>
![AMRhierarchy](images/Butterfly-gen_AMRhierarchy.png?raw=true "Butterfly Graphical View of function gen_AMRhierarchy.c")
Only run AHF when the finest grid level has been reached 
Image Vtune: gen_AMRhierarchy called recursively 


function: gen_refgrid\
lot of time spent with io

#### Use of OpenMP:
file: specific.c </br>
![specific](images/Butterfly-specific-c.png?raw=true "Butterfly Graphical View of function specific.c")
which writes the log output, colecting and processing data of others functions results

#### AHF Metrics: 
Blank Lines 9.521\
Classes 0\
Code Lines 35.150\
Comment Lines 16.428\
Comment to Code Ratio 0,47\
Declarative Statements 6.239\
Executable Statements 22.222\
Files 246\
Functions 962\
Inactive Lines 25.224\
Lines 89.784\
Preprocessor Lines 6.499\
