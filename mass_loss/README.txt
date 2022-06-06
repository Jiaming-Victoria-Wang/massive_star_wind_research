2022 June 6,
Victoria Wang

This folder contains all the files needed to produce figure 4 in the Cohen et al. 2021 paper, and the mass loss rate pdf distributions for both cyclce 1 and cycle 19.

To produce the taustar vs. wavelength figure for cycle 19 or cycle 1, copy the 10 Cstats_tau.txt files in the corresponding subfolders into the main folder. Run the massloss_prob.ipynb code, and adjust the first two lines in cell 3, which specifies the cycle number. Cell 4 defines stellar and wind parameters which can also be adjusted (but better left consistent). Cell 5 contains the find68Err function, which can be helpful in finding the 68% confidence region of any given distribution.

The input files for the massloss_prob.ipynb code are the 10 Cstats_tau.txt files; the kappaZ.txt files (a tabulation of kappa vs. wavelength); and the cycle19_mass_loss_pdf.txt and the cycle1_mass_loss_pdf.txt. The last two files are used to produce the inserted figure on the top left corner that compares the mass loss rate pdf of the two cycles. Once the two files are in the main folder, the writeProb command in cell 9 can be commented out to avoid adjustments of these files. 

