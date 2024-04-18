Run the following commands in order after installing OpenFOAM

1) blockMesh
2) surfaceFeatures
3) snappyHexMesh -overwrite
4) simpleFOAM
5) foamToVTK

Then visualize on paraview. Please set the required mesh in the constant folder and boundary conditions in the 0 folder.
