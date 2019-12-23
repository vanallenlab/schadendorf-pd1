# schadendorf-pd1

This repository provides sample code to reproduce figures from Liu, Schilling, et al, Integrative molecular and clinical modeling of clinical outcomes to PD1 blockade in patients with metastatic melanoma, Nat Med 2019 (PMID: 31792460 DOI: 10.1038/s41591-019-0654-5) with associated source data (supplemental data and tables from the paper).

Due to space constraints, data available at the published paper website is not provided here and must be separately downloaded (see Instructions).

Notes:
- environment.yml contains package versions (created using "conda env export > environment.yml")
additional data files are provided in data/addData.zip:
- rnaseq_rawcounts.txt: RNAseq raw counts matrix
- geneTumorMatrix.txt: a matrix of genes x patients with mutation status as entry
- nanostring_genes.txt: set of overlapping genes between RNAseq and the Nanostring assay
- manguso_genes.txt: set of genes found in in-vivo CRISPR screen (Manguso et al Nature 2017) for response or resistance to PD-1 ICB immunotherapy
- updated_ssGSEA_SuppData.txt: updated Supplemental Info table for ssGSEA signature scores (sheet "ssGSEA geneset scores" in Supplementary_Data.xlsx in the published files)

Figures-NatMed.ipynb is a Jupyter Notebook (Python 2.7 kernel) containing sample code to reproduce paper figures. 

Additional Instructions:

Download the following files from the Nature Medicine website and add them to the 'data/' directory:
- CNA_matrix.xlsx
- RNA_TPM_matrix.txt
- Supplemental_Tables.xlsx
- Supplementary_Data.xlsx

unzip the 'addData.zip' files before running the notebook


Please contact a corresponding author for any questions, comments, or concerns regarding the paper in general.
EliezerM_VanAllen@DFCI.HARVARD.EDU
dirk.schadendorf@uk-essen.de
