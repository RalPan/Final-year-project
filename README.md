# Final-year-project
For my master's thesis I investigated the use of machine learning in vortex systems, more specifically, in the mixed state of type II superconductors. This repository contains two reports, four Jupyter notebooks containing the code developed, and four csv files.

The Jupyter notebooks included are:

- Melting.ipynb is the main notebook containing the code for simulating the material and training the machine learning model. Due to the long time it takes to run a simulation, the data from a previous run was saved and included in this repository, enabling the notebook to be run without needing to wait for the simulation.
- Benchmark1_lattice.ipynb is a benchamrk test done to ensure that the forces between vortices were modeled correctly.
- Benchmark2_channel.ipynb is a benchamrk test done to ensure the strenght of the force used was accurate.
- Build logistic regresion.ipynb is a short notebook where I built a logistic regresion algorithm to classify a test data set.

The reposts contained are:

- The final report: closely follows the work done in the notebook Melting.ipynb.
- The preliminary report: explains the work done in the first term, which are the benchmark tests present in Benchmark1_lattice.ipynb and Benchmark2_channel.ipynb.
