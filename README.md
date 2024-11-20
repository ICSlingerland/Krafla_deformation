**InSAR Velocity Analysis in the Krafla Area**

This project was for the Iceland fieldtrip as part of the Master Applied Earth Science, TU delft.

This repository contains 3 Jupyter Notebooks for analyzing and visualizing InSAR velocity signals in the Krafla volcanic area. 

- The notebook *Krafla Region Map* shows a map of the region.
- The notebook *insar_deformation_krafla* is designed to process Insar data and give insights into ground deformation patterns derived from InSAR measurements.
In the Krafla area are several physical proccesses that cause deformation, such as plate spreading, active volcanism, geothermal activity and uplift due to Glacial Isostatic Adjustment. 
The Insar notebook is used to isolate the plate spreading velocity, by decompising the line of sight velocity into 3 components.
The component paralel to the plate is set to be 0 and therefore the signal can be composed in 2 components vertical and perpendicular to the plates fracture.
This plate velocity signal is modeled by rotating the reference system, meaning that now the plate velocity only depends on one dimension.
The signal has to be brought back to the LoS signal and rotated back and is then subtracted from the total signal. 
This gives a residual signal.
- The last notebook *insar_time_series* just shows a timeseries of points/areas of interest. This was used to make an initial fieldcampaign plan to decide where to take measurements.






