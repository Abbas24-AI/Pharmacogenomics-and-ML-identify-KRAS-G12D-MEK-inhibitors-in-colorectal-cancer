# Pharmacogenomics-and-ML-identify-KRAS-G12D-MEK-inhibitors-in-colorectal-cancer

This repository contains a reproducible, end-to-end computational pipeline integrating pharmacogenomics, bulk transcriptomics, single-cell RNA sequencing, chemoinformatics, and supervised machine learning to identify drug-sensitivity determinants and candidate inhibitors targeting KRAS-G12D–MEK signaling in colorectal cancer.

## Pipeline Overview

The workflow consists of the following steps:

1. Integration of CCLE expression, mutation, and metadata
2. Harmonization of GDSC drug response (IC50) data
3. Correlation analysis between KRAS expression and drug sensitivity
4. Selection of biologically relevant reference inhibitors
5. Single-cell RNA-seq analysis for KRAS expression heterogeneity
6. ChEMBL-based chemoinformatics data processing
7. Molecular fingerprint generation and supervised ML modeling
8. Similarity-based ranking against reference MEK inhibitor (Selumetinib)
9. Consensus filtering to prioritize high-confidence drug candidates

## Data Sources

The following publicly available datasets are used:

- CCLE (DepMap):
- GDSC (Genomics of Drug Sensitivity in Cancer):
- Single-cell RNA-seq:
- ChEMBL Database:

*Note: Raw data files are not included in this repository and must be downloaded
from the original sources due to size and licensing restrictions.*

## Dependencies

Python ≥ 3.8
Key packages:
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [scipy](https://scipy.org/)
- [scikit-learn](https://scikit-learn.org/)
- [scanpy](https://scanpy.readthedocs.io/)
- [seaborn](https://seaborn.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [RDKit](https://www.rdkit.org/)

## Clone the Repository
To get the code locally:

Clone the repository

```bash
git clone https://github.com/Abbas24-AI/Pharmacogenomics-and-ML-identify-KRAS-G12D-MEK-inhibitors-in-colorectal-cancer.git
```

Navigate into the directory
```
cd Pharmacogenomics-and-ML-identify-KRAS-G12D-MEK-inhibitors-in-colorectal-cancer
```
Launch Jupyter Notebook

```
jupyter notebook Integrative_Pharmacogenomics_ML_KRASG12D_MEK_CRC.ipynb
```


## Citation

In process.

## Contacts

**Abbas Khan**  
*Department of Biomedical Sciences, Sir Jeffrey Cheah Sunway Medical School, Faculty of Medical and Life Sciences, Sunway University*  
📧 Email: [abbask@sunway.edu.my](mailto:abbask@sunway.edu.my)

