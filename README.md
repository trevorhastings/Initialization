# Initialization

Data used for the Initialization of Optimization problems.

The Bayesian Optimization code for this work can be found in https://github.com/trevorhastings/HTMDEC. It is applicable to the starting datasets found in these folders.

Several datasets were used for these simulations:

1) A general downselection of the HTMDEC dataset. This datasets is comprised of the Al-V-Cr-Fe-Co-Ni space in 5% increments, reduced to 2,000 representative data points with the k-medoids algorithm. It contains several basic CALPHAD property predictions from Thermo-Calc for output simulations.

2) A specific downselection of the HTMDEC dataset where the nonzero elements within it were maintained. This is a simple reduction done in code from the main dataset.

3) A dataset from a refractory alloy project, which can be found here. This dataset was reduced from the Ti-V-Nb-Mo-Hf-Ta-W space to 1,000 data points for optimization.

4) Two iterations of experimental data from the refractory alloy space.

Other datasets, such as experimental data from HTMDEC or the popular Borg dataset for compression tested alloys, were tested internally as part of code verification but do not appear in the work.
