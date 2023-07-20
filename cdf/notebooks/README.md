# Methodologies for assigning census tracts to libraries and census data pull

# Introduction
Assigning census tracts to the corresponding library locations is the first step in understanding community needs, optimizing library resources, and analyzing service accessibility. The notebooks/scripts contain code for different methods in creating these assignments as well as an ability to aggregate census data based on assignments. 

# Scripts
**acs_pill.py** - This notebook focuses on extracting predefined sociodemographic data from the ACS for the Chicago.

**m1.ipynb** - This notebook focuses on assignments using 1 mile buffer zone and shortest euclidean distances from census tract centorids to libraries

**m2.ipynb** - This notebook focuses on assignment using majority area of census tract in 1 mile buffer zone and shortest driving distances from census tract centroids and libraries 

