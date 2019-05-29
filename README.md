# Private Causal Inference using Propensity Scores

This is the code for reproducing the figures and tables for the paper [Private Causal Inference using Propensity Scores](arvix.org).

For figure 1, both plots are produced by running tau_bias_sim.ipynb.
For figure 2, plots (a) and (b) are produced by running epsilon_sim.ipynb and setting the variable tau to be 0.1 and 2 
while plots (c) and (d) are produced by running n_sim.ipynb and setting the variable tau to be 0.1 and 2.

The contents of table 1 are produced by running epsilon_ihdp.ipynb and epsilon_lalonde.ipynb. To get the former working, please
download the IHDP [train](http://www.fredjo.com/files/ihdp_npci_1-100.train.npz) and [test](http://www.fredjo.com/files/ihdp_npci_1-100.test.npz)
datasets and put them in a new folder in data called IHDP-1000. The latter data is already provided. 
