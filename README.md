# Simple PCB cooling tutorial openfoam
　This is an openfoam analysis case for a simple PCB cooling simulation. The solver used is `chtMutiRegionFoam`.
# OpenFOAM version
  This case is tested with OpenFOAM v2312.
# How to run
  1. Download the case files.
  2. Unzip the files to your OpenFOAM case directory.
  3. Edit the file (Example: `system/topoSetDict`) and run the simulation with the command:
      ```bash
      cd simple_pcb_thermal_simulation
      ./Allrun
      ```
  4. Visualize the results with Paraview or any other OpenFOAM compatible visualization tool.

  > **Note:**  
  > A 14-core parallel run is used in this case. You can change the number of cores by editing the `system/decomposeParDict` script.
