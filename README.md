# OpenFOAM_laminar_BL
This is a laminar boundary layer problem solution of flow over a flat plate using OpenFOAM icoFoam solver.

The boundary conditions used in the U file are...

zeroGradient on the top and bottom of the flow entrance region.
constrant velocity on left side of the flow entrance region.
zeroGradient on top of the flat plate region and the right hand side.
noSlip condition on the bottom of flat plate region.

for the furture, turbulence modeeling can be included (can be do it in an another respository)..
