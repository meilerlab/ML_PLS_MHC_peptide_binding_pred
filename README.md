
# ML_PLS_MHC_peptide_binding_pred
This repository introduces a machine learning application using Partial Least Squares (PLS) to predict the binding affinity between MHC (A0201) and peptides of 9 or 10 amino acids in length, including at least one non-canonical amino acid.

## Background
Major histocompatibility complex (MHC)-I molecules, encoded by the HLA-A, HLA-B, and HLA-C genes, present peptide fragments on cell surfaces for recognition by CD8+ T cells. An antigen's ability to induce a T cell response is linked to its binding affinity for MHC-I. While existing tools predict this affinity, none address antigens with post-translational modifications or non-canonical amino acids (NCAAs), which are crucial for peptide immunogenicity. This project proposes a machine learning application using PLS to quantify the binding affinity of epitopes with NCAAs to MHC-I and compares its performance with other common regressors.

## Files
The repository contains five files:

Four Jupyter notebooks with codes and results for the project.
One zipped file named csv, including CSV files needed for running the Jupyter notebooks.
The original CSV files were downloaded from IEDB(https://www.iedb.org/).

## Environment
The Jupyter notebook named "script3" needs to be opened and run in the RDKit environment. Installation instructions for RDKit can be found from https://www.rdkit.org/docs/Install.html.

