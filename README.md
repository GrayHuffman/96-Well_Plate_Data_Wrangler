# 96-Well_Plate_Data_Wrangler
This R script reformats 96-well plate luciferase assay results for ease of statistical comparison

If each of the twelve columns of your 96-well plate represent 8 replicates from a given sample, this short R script will reformat the proprietary plate-reader data format to two columns of data: one for your assay measurements and one for your sample labels

In order to use this script, you need to have the readxl and reshape2 packages installed.

Additionally, you will need to specify the location of your initial assay file in the wellPlate variable (line 20) and your preferred output location in write.table (line 29).
