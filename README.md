# treeterm-paper
Scripts for generating the simulation

- sim_data: simulation related files
  - Snakefile - Entire pipeline from generating the fastqs to running TreeTerminus for the simulated data. Two variations generated through Snakemake which takes **config.json** as input and is present in *brain_sim* and *brain_sim_lowfc* folders.
  - brain_sim - Normal simulation
  - brain_sim_lowfc - Simulation in which the log fold change is lowered between the conditions
  - Remaining files and folders are the inputs used for generating the required inputs to **Polyester**.
- sessionInfo.txt - All **R** packages that have been used in the **TreeTerminus** paper.


