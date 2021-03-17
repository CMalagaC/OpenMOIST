# OpenMoist_2021_V1 Input Data

First you have provide the address of the file containing of the environmental conditions.

As an example for the case of a solid rectangular section: ("D:\Results\Timber Moisture Transport\Script\ENVIRON-COND-SOLID.xlsx",sheet_name="Sheet1",index_col=None,header=0)

As an example for the case of a hollow rectangular section: (D:\Results\Timber Moisture Transport\Script\ENVIRON-COND-HOLLOW.xlsx",sheet_name="Sheet1",index_col=None,header=0) & ("D:\Results\Timber Moisture Transport\Script\ENVIRON-COND-HOLLOW.xlsx",sheet_name="Sheet2",index_col=None,header=0)

The files have to follow the format of the xlsx. files attached in the OpenMoist_2021_V1 folder. 
These files were used in the analysis of the sections. Then you have to enter the geometry data in
the same units as in the round brackets, the initial moisture content and the adopted discretization 
for the mesh of the analysis. Finally, you are allowed to change the input local functions for
the diffusion coefficient and surface emissivity with relationships describing these variations.

# OpenMoist_2021_V1 Output Data

It is suggested to run the python code in a Jupyter Notebook to obtain a good display of the mesh
during the analysis. You will obtain a plot displaying the moisture variations at selected nodes
and an xlsx. output file in the same address of the xlsx. input file containing all the moisture 
variations across the whole section. 

-- C. Melchor-Placencia, Christian Malaga-Chuquitaypea
