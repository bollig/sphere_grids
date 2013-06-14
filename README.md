sphere_grids
============

Grids on the unit sphere used as test cases for my dissertation



MD node sets come with 4 columns. The 4th column is the quadrature weight. 
To get only the Cartesian coordinates from the node sets, use: 

cut -d' ' -f4- input_grid > output_file
