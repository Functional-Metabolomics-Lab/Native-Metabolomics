# Native-Metabolomics-1
Code and Documentation for Native Metabolomics Workflow Mass-Offset Matching.
This Jupyter Notebook allows for mass offset matching between two metabolomics feature tables (matrix with m/z and RT values).
Two feature table csv files that are supposed to be matched with a defined mass difference (e.g. intact protein mass) need to be specified in the notebook along with mass and RT tolerance.
The output files contain a merged feature table that lists all redundant matched feature pairs.
Example input files are provided (Metabolites_Example.csv and Protein_Example.csv).
