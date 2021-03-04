# LSST-BD-Cadence
notebooks for brown dwarf related calculations for Vera C. Rubin Observatory LSST. Aimed at developing a Cadence Note to the SCOC.  

Numbers_for_Note notebook has the actual Figure of Metric (observable volume of L7 dwarfs) divided by the baseline. Meant to give numbers for the document. 

Brown_Dwarf_LF_LSST has information on the absolute magnitudes and space densities of L,T dwarfs as a function of spectral type.
[Y dwarfs are faint anyway so not considered]

The remaining notebooks are designed to work on NOIRLab DataLab notebooks.  You have to use the LSST MAF kernel. See the Jones cadence report (PSTN-051) 
and community.lsst.org for descriptions of the simulation families and their purpose.

bd_dist_metric runs through the baseline 1.7 cadence simulation for a variety of spectral types.  

The bd_L7_* notebooks loop through the simulations for various families for the L7 spectral type.  

bd_L7_baseline15.ipynb       -> the 1.5 baseline.

bd_L7_bulges.ipynb           -> 1.5 simulations covering Galactic plane, bulge

bd_L7_filters.ipynb          -> 1.5 all-sky simulations varying the filter weighting. Should have been called filt_dist. 

bd_L7_footprints.ipynb       -> 1.5 simulations varying the footprint

bd_L7_wfd_depth.ipynb        -> 1.5 simulations varting the depth of WFD.


bd_L7_even_filters_1.6.ipynb  -> 1.6 with strategy to even out filter visits/depths

bd_L7_rolling_fpo_1.6.ipynb   -> 1.6  with rolling cadence 

bd_L7_pot_sched_1.6.ipynb     -> 1.6 potential schedulers implement multiple changes at once! 

bd_L7_wfd_depth.ipynb         -> 1.6 varies survey time spent on WFD from 65% to 99%. 


bd_L7_footprint_baseline_1.7.ipynb   -> 1.7 baseline with 2 snaps or 1 snap. 2 snaps is official

bd_L7_footprint_tune_1.7.ipynb       -> 1.7 trying to finetune the on-sky footprints





