# Native-Metabolomics
Code and Documentation for Native Metabolomics Workflow Mass-Offset Matching
This jumpyter Noteboke allows for mass offset matching between to metabolomics feature tables (matrix with m/z and RT values).
Two features tables csv files that are supposed te be matched with a defined mass difference (e.g. intact protein mass) need to be specified in the notebook along with mass and RT tolerance.
The output files contains a merged feature table that lists all redundant matched feature pairs.
Example input filed are provided (Metabolites_Example.csv and Protein_Example.csv).
