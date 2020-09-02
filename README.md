# Features:
- user friendly: users input data in minimal code blocks
- saves images to indicated directory/folder
- variable names are used to make pipeline flexible for multiple experimental conditions
- R markdown feature allows for preservation of settings used and figures generated for later reference
- dataframes are exported to indicated directory/folder for downstream analysis in other applications

# Usage:
1. Compensate flow cytometry data and gate to population of interest.
2. Concatenate all samples and export as .csv file. Make sure you know the order of the samples.
3. Make a metadata table (see example below) and save as .csv
4. Open .Rmd file and follow instructions in document.

# Example metadata table
sample  treatment
1           A
2           A
3           A
4           B
5           B
6           B
