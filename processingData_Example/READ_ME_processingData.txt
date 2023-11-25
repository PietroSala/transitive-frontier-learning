
## Dimensione AQuality: 
	row: 9356
	used columns : CO_GT, PT08_S1_CO, NMHC_GT, C6H6_GT, PT08_S2_NMHC, NOx_GT, PT08_S3_NOx, NO2_GT, PT08_S4_NO2, PT08_S5_O3 

# Acronimi file (per praticità):
	- RCE     : R: Random child,  C: digit priority Complete, E: saturate Effective
	- RCA     : R: Random child,  C: digit priority Complete, A: saturate All
	- RSE     : R: Random child,  S: digit priority Simple,     E: saturate Effective
	- RSA     : R: Random child,  S: digit priority Simple,     A: saturate All
	- RC_ud :  R: Random child,  C: digit priority Complete, _ud: Up-Down (It's possible enable/disable the analysis of RC_ud together with other results)

# NB: All test without a priority surpass the time limit for the analysis (10-12 hours) 
# NB: RC_ud  has not subrun

# File to reprocessing the results
	- data_raw 
	- ProcessingResults_1_Rules_SuppConfGeneraliz
	- ProcessingResults_2_Plotting_Run_NsuppNconfConf
	- ProcessingResults_3_Plotting_SubRuns

# Files needed(same directory):
	- myFunctions
	- Functions_ProcessingResults 
	
# Requirements:
	- pandas 
	- numpy 
	- pydotplus 
	- import_ipynb
	- datetime 
	- matplotlib
	- math



