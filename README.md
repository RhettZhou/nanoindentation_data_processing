# nanoindentation_data_processing

By Xuyang (Rhett) Zhou at Max-Planck-Institut für Eisenforschung GmbH, 2021/05/14 13:16

This code aims to enable fast data processing when one has several nanoindentation results and wants to compare these results together.

First, the user can place all the experiment files (.xls files) in a folder where the individual files are named one after the other. 

In step 2, the user can select any of the .xls files to start with. Then the user can specify the structure of the naming (up to 3 levels are supported). All the raw data points in each region of interest (ROI) are plotted and save in the subfolder 'png'.

In step 3, the user can select the nonsensical data points, label them and exclude them for later statistical analysis. This step is important as there may be contaminants on the surface of your sample that will affect the reliability of your measurements. The remaining data points in each region of interest (ROI) are also plotted and save in the subfolder 'png'. After completing the entire step 3, the metadata has been saved and is ready for the next use. 

Step 4 offers the possibility to plot all curves together and draw the statistical results.
