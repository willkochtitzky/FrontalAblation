# FrontalAblation
23 June, 2022
This code is associated with two publications that will be updated when the mansucripts are published and availible online

The code was developed from 2020 to 2022 to calculate the frontal ablation of Northern Hemisphere glaciers by Will Kochtitzky at the University of Ottawa.
This script requires many inputs that are combined to compute frontal ablation and you will not be able to run the script on your own (regretfully) without these specific inputs (see file paths in the jupyter notebook).
If you are interested in working with this script on your own, please contact me (willkochtitzky@gmail.com) and I can help you, gladly.
I make the script availible here because bad code is better than no code. I am happy to help you if you have questions about these scripts

I have also included a yml file to set up the environment that I ran this script in. This can be installed with Anaconda.

This repository has four scripts: two of which will compute frontal ablation (without_plots) and the others which will generate all the plots in our publications (plots_only).

Greenland_frontal_ablation_plots_only_v1.ipynb - generate all the plots that make up the publication
Greenland_Frontal_Ablation_v3.ipynb - the script that combines observations (thickness, velocity, etc) into frontal ablation estimates
Pan_Arctic_Discharge_v7_plots_only_v3.ipynb - generate all the plots that make up the publication
Pan_Arctic_discharge_v7_without_plots_v10.ipynb - the script that combines observations (thickness, velocity, etc) into frontal ablation estimates

Pan_Arctic_discharge_v7_regional_error_calculations_v2.ipynb - this script will compute the regional error analysis given the inputs from the Pan_Arctic_discharge_v7_without_plots_v10.ipynb script.

The two scripts to generate frontal ablation estimates are extremely similar (the Pan_Arctic script was developed first).

I apoligize that this code is not commented or well documented and you will not be able to run it without the file structures that exsist on my computer. However, please reach out and I am happy to help you with whatever relevent project you may be working on.
The script is unlikely to be updated as it is the script for a specific project and will need to be written differently when we update frontal ablation next.
If you need to make frontal ablation calculations for a specific glacier, or a group of glaciers, it will be much easier to do that on your own than to use this script. This script is designed for hemsipheric scale analysis and makes some assumptions to do that, which you can improve on for specific locations where more expert knowledge exists.

We also provide the geopackage file (EPSG 3995) that contains the fluxgates used in this analysis for mountain glaciers. These fluxgates were clipped with a slightly edited version of the RGI6 outlines, so are not the final segments used for data extract in this work (see script for how this is done). Contact me and I can give you the individual points where we extracted data along these lines, the file is too big to upload to Github.
For files associated with Greenland frontal ablation, please see the Polar Data Catalogue dataset number 13272
