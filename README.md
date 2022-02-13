# Modeling Brain Dynamics in Brain Tumor Patients Using the Virtual Brain  
In this demo, we show how to simulate large-scale brain dynamics using The Virtual Brain, an open-source neuroinformatics platform. 
## Introduction  
We 
## Load Individual Connectivity
Connectivity input data can be found in 
<br>
Put Input data folder in the same directory of this python notebook.
Input data needs to follow the directory structure below:
```
TVB_bbt.ipynb
TVB_input
│   CONXXTX (Control/Patients + number + T1/T2)
│   │   FC.mat
│   │   SCthrAn.mat
│   └───CON02T1_TVB.zip
│       │   areas.txt
│       │   average_orientations.txt
│       │   centres.txt
│       │   cortical.txt
│       │   hemisphere.txt
│       │   tract_lengths.txt.txt
│       │   weights.txt
│   
└───CONXXTX
    │   ...
```
