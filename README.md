# Flow Cytometry Clustering and Visualization Pipeline using R
## Features:
- user friendly: users input data in minimal code blocks
- saves figures to indicated directory/folder
- variable names are used to make pipeline flexible for multiple experimental conditions
- R markdown feature allows for preservation of settings used and figures generated for later reference
- dataframes are exported to indicated directory/folder for downstream analysis in other applications
- Currently, colors are set using hex codes, and **support up to 15 groups in the template**. This can be changed/edited as desired by using a hex color picker for the codes (google search "hex color picker" for a good one).

## Usage:
1. Compensate flow cytometry data and gate to population of interest.
2. Export all samples individually as .csv files using **CHANNEL** values (not scale values). Most times compensated values are used. Make sure "export_" is in the exported file name.
4. Make a metadata table (see example below) and save as .csv file. 
5. Open .Rmd file and follow instructions in document.

## Files:
- use generic pipeline file for 2 groups
- use 3 group file for 3 groups

## Example metadata table
file_name | sample_id  | group
------------- |------------- | -------------
export_Specimen_001_2055 CD45+ | 2055 | A
export_Specimen_001_2056 CD45+ | 2056 | A
export_Specimen_001_2057 CD45+ | 2057 | B
export_Specimen_001_2058 CD45+ | 2058 | A
export_Specimen_001_2059 CD45+ | 2059 | B
export_Specimen_001_2060 CD45+ | 2060 | B
export_Specimen_001_2061 CD45+ | 2061 | A
