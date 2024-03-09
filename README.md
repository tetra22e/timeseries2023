Below, please find a description of the folders/files used for this project.

There are two main types of files/analyses used in this project: gene expression analysis via qPCR, and shape trajectory analysis via geometric morphometrics.

Folder: Labeotropheus_txt_wholeshape; Maylandia_txt_wholeshape; Tropheops_txt_wholeshape
The files in these three folders contain all the txt files for each denoted species of landmarking data for the whole shape of the head. Each file name describes the treatment (Benthic=Ben; Pelagic=Pel) and the number of weeks each individual was part of the experiment (1wk; 2wk; 4wk; 8wk). Within each file is positional data for 11 fixed landmarks and 2 curves (i.e. the slope of the face and the eye). All files in these folders were used to generate Figure 4 and Figure S2.

File: MasterCSV_wholeshape.csv
This file simply describes each individual’s identity (column 1=ID), their species (column 2=Species), the experimental treatment (column 3=Treatment), and the duration they were in the experiment (column 4=Time).

File: Wholeshape_landmarks.txt
This file describes each fixed landmark and its position on the face and was used in conjunction with Wholeshape_curves.txt to landmark each individual.

File: Wholeshape_curves.txt
This txt file simple describes where each of two curves is located, the profile of the face between fixed landmarks 1 and 2, and the continuous curve around the eye.

File: Linkages_residuals_timeseries_compiled.csv
This csv contains the species (column 1), treatment (column 2), species by treatment (column 3), duration of treatment by week (column 4), species by treatment by week (column 5), and ID number (column 6) for each individual. In addition, linear measures of length were generated in ImageJ of the head (column 7, HL), fixed linkage (column 8, FL), input linkage (column 9, IL), coupler linkage (column 10, CL), and output linkage (column 11, OL). Residual values were calculated for each linkage length except the fixed link by head length (columns 12-14), but were not used in the dataset. The rest of the file contains statistical analysis results with a species between treatments for any given week in terms of linkage length, and also the differences in growth slopes between species across all timepoints or between treatments within a species. Data in this file were used to generate Figure 3.

File: cichlid_timeseries_expression_compiled_all.csv
This csv file contains deltaCt values for a panel of genes deemed important in plasticity, species differences,  and bone shape/growth (columns 4-12), in addition to species (column 1), time in the experiment (column 2), and treatment (column 3) for each individual. Data in this file were used to generate Figure 2 and Figure S1.
