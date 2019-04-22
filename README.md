# Scripts for in-house use on the ABIDE and AIMS data

Can be probably used on other rs-fMRI data

These scripts usually use:
Standard bash commands
Various afni programs
Various fsl programs
Python2 and 3 and various librarys within there - including all anacoda libraries.
Some matlab and SPM12 scripts


These scripts are meant to be complementary to speedyppX.py, which is our main preprocessing pipeline.

De-noising module adapted for motion artifact removal by Patel, AX. (2014).


Alphabetical list of scripts and short bio:

BET_runsecondrun.sh - Extensive bet, other than the speedy default.__
Clean_up_beforedoing_speedy.sh - Deprecated, use Remove_after_speedy.sh for similar things.__
export_good_stuff.sh - Extracts useful output from the preprocessed directories.__
FCN.m - IGNORE it - Attempt to make Functional Connectivity script.__
Hmap_Loop.m - Loops over sucjects and calls compute_hmap.m.__
Male_hurst_analysis_MRC.py - Mass Univariate T-test on parcellated Hurst in AIMS.__
Male_hurst_analysis_USM_Scans.py - Mass Univariate T-test on Hurst in ABIDE_1 USM.__
Mean_FD_looper.sh - extracts Mean_FD from rest_motion_fd_summary_stats.csv.__
Melodic_DualR.sh - Dual regression with FSL.__
N_vols.sh - Finds number of volumes from ABIDE data.__
plot_fd_dvars.py - Plots fd and dvars.__
plot_fd_dvars_looper.sh - Loops plot_fd_dvars.py on ABIDE data.__
Powerspectrum_loop.m - Makes various PSD plots from timeseries csvs.__
Preprocessing_Script_Master_1.sh - Main preprocessing pipeline for rsfMRI data.__
Remove_after_speedy.sh - Removes things from the final preprocessing dir for space saving.__
Summary_csv_looper.py - MeanFD_looper.sh depends on this to exract MeanFD.__
UBUNTU_largest_grid.sh - Calculates number of voxels for each subject for ABIDE data.__
UBUNTU_largest_grid_Step2.sh - Finds single subjects with the largest grid, for ABIDE.__


