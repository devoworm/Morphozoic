Morphogenetic fields.

Run the gastrulation application and click on a cell to see the surrounding fields.
Cycle through the field spheres with the space bar.
Click within a sphere sector to see its cell type densities.

To generate and save metamorph "templates":
java -jar morphozoic.jar -genMetamorphs metamorphs.dat

To load and run using the metamorph templates:
java -jar morphozoic.jar -execMetamorphs metamorphs.dat

To run the Game of Life application, specify with the -organism option:
java -jar morphozoic.jar -organism morphozoic.applications.GameOfLife

To run the C elegans application, specify with the -organism option:
java -jar morphozoic.jar -organism morphozoic.applications.Celegans
