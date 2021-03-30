# Flow Cytometry Clustering and Visualization Pipeline using R
## Features:
- user friendly: users input data in minimal code blocks
- saves figures to indicated directory/folder
- variable names are used to make pipeline flexible for multiple experimental conditions
- R markdown feature allows for preservation of settings used and figures generated for later reference
- dataframes are exported to indicated directory/folder for downstream analysis in other applications

## Usage:
1. Compensate flow cytometry data and gate to population of interest.
2. Export all samples individually as .csv files. Make sure "export_" is in the exported file name.
3. Make a metadata table (see example below) and save as .csv file.
4. Open .Rmd file and follow instructions in document.

## Example metadata table
filename | sample_id  | group
------------- |------------- | -------------
export_Specimen_001_2055 CD45+ | 2055 | A
export_Specimen_001_2056 CD45+ | 2056 | A
export_Specimen_001_2057 CD45+ | 2057 | B
export_Specimen_001_2058 CD45+ | 2058 | A
export_Specimen_001_2059 CD45+ | 2059 | B
export_Specimen_001_2060 CD45+ | 2060 | B
export_Specimen_001_2061 CD45+ | 2061 | A
