# Geoclassification
This code library describes a machine learning approach to determine the geographic origin of whole-genome sequenced malaria parasite isolates. A manuscript detailing the method is forthcoming.

# Installation
The main code is included in a Jupyter Python notebook. The script requires installation of a number of python packages. The following versions of key packages were used: 
python sys.version_info(major=2, minor=7, micro=16, releaselevel='final', serial=0); pandas 0.24.2; numpy 1.16.5; sklearn 0.20.3

# Notes
The notebook uses a simulated dataset (Dummy_Dataset_2A.xlsx). Any real datasets should be formatted in the same manner (e.g. column names) as the simulated dataset. For some datasets, we encountered a memory error when running the lasso regressions in a parallel manner. If you encounter the same error, we suggest setting n_jobs equal to 1. 
