2022 June 6,
Victoria Wang

This folder contains the code Cstats.ipynb that plots the probability density distributions for uo, Ro, and taustar. It also writes out the pdf in a txt file. The taustar pdf txt files are used in the massloss_prob.ipynb code in the lineprof_massloss folder.

The input file for Cstats.ipynb is a three-column txt file. The columns represents delta C values, taustar, and u0 respectively. To generate the txt file, issue the command steppar in xspec with correct syntax (remember to log output before doing steppar), copy the output log file into the current folder, delete unnecessary rows, delete the "#" signs in each row using option+shift (which lets you delete by columns instead of by rows). You then should get a five-column file. Run it through modify_Cstatstxt.ipynb to get rid of unnecessary columns. The resulting three-column file should be ready to go.

The Cstats.ipynb code can also plot pdf for sigmastar, from a two-column txt file. See the commented out lines in the code.
