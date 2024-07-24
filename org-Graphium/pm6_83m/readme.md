## Background
PM6_83M dataset is similar to the PCQM4M and comes from the same PubChemQC project. However, it uses the PM6 semi-empirical computation of the quantum properties, which is orders of magnitude faster than DFT computation at the expense of less accuracy.

This dataset covers 83M unique molecules, 62 graph-level tasks, and 7 node-level tasks. To our knowledge, this is the largest dataset available for training 2D-GNNs regarding the number of unique molecules. The various tasks come from four different molecular states, namely S0'' for the ground state,T0'' for the lowest energy triplet excited state, cation'' for the positively charged state, andanion'' for the negatively charged state. In total, there are 221M PM6 computations.