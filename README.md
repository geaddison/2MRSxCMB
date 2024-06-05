# 2MRSxCMB
Code to perform calculations from Addison (2024), 'Does the Correlation between 2MRS Galaxies and the CMB Indicate an Unmodeled CMB Foreground?' (paper accepted for publication by Astrophysical Journal and available on arXiv at https://arxiv.org/abs/2403.10490).

The code is provided in the Jupyter Notebook addison_2mrs_cmb_correlation.ipynb.

The repository also contains a data/ directory containing a copy of the 2MASS Redshift Survey galaxy catalog used in the analysis (obtained from the 2MRS website http://tdc-www.cfa.harvard.edu/2mrs/), as well as .npy arrays containing the $\Delta T(\theta)$ correlation statistic (see equation 1 of the paper) from correlating the 2MRS catalogs against simulated CMB maps. Code to reproduce and read these files is included in the Notebook.

The Planck CMB maps used in the analysis can be downloaded from the Planck Legacy Archive (PLA) at http://pla.esac.esa.int/pla/#maps. The SMICA CMB map and mask are contained in the file COM_CMB_IQU-smica_2048_R3.00_full.fits (click Maps -> CMB maps -> SMICA -> FULL MISSION in the PLA interface).

## Contact ##

Graeme Addison - gaddison@jhu.edu
