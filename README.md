# TTM_Grid_Datasort_Graphplot

 "--------------------------------------------------------------------------"
    " MATLAB Script: TTM_Grid_Datasort_Graphplot"
    "--------------------------------------------------------------------------"
    ""
    " File: TTM_Grid_Datasort_Graphplot.mlx"
    " Description: This script demonstrates a MATLAB Code."
    " Author: Shorup Chanda"
    " Created: 2023-08-11"
    " Last Modified: 2023-08-11"
    ""
    " Copyright Notice:"
    " (c) 2023 Shorup Chanda. All rights reserved."
    " This code may not be used or distributed without permission."
    ""
    "--------------------------------------------------------------------------"

This Script Allows Data sorting and Plot The Temperature Distribution in a Specific Grid. This is only applicable to my output format from Lammps.
This is a life-saving code of MATLAB for TTM simulations.
When I build this code I was working with Selective laser Melting using Two Temperature Model.
During the simulation, I found about 500 files in T_out_*.txt format as output. 
I need to sort the files and select a specific row from each of the files which is basically time-consuming when you do it manually.
So, I use MATLAB to sort the files, take them in a matrix format and input the data of the files in another variable and then plot the graphs.

Finally, It gives me an output of a sorted table and plot of Lattice temperature and Electron Temperature. 
