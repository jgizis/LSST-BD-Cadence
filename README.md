# LSST-BD-Cadence
notebooks for brown dwarf related calculations for Vera C. Rubin Observatory LSST. Aimed at developing a Cadence Note to the SCOC.  

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



