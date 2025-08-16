# Notebooks

This folder contains Jupyter notebooks used in the construction and refinement of the **Bangladesh Electricity Dataset (2019–2024)**. Each notebook corresponds to a stage in the pipeline, from raw data scraping to preprocessing and validation.

### Contents

* **`01_bpdb_pdf_scraping.ipynb`**
  Notebook for scraping daily electricity reports from the **Bangladesh Power Development Board (BPDB)** digital archive and extracting tabular data from PDF files into structured Excel/CSV format.

* **`02_data_preprocessing.ipynb`**
  Notebook for cleaning and preprocessing the extracted data, including duplicate removal, missing value handling, outlier correction, holiday classification, and temporal feature engineering.

* **`readme.md` (this file)**
  Provides documentation for the notebook workflow and file naming conventions.

### Notes

* File names follow the convention:
  `01_<task>.ipynb`, `02_<task>.ipynb`, … to indicate execution order.
* The scraping and preprocessing steps together reproduce the dataset described in the *Data in Brief* article (under review) and the deep learning analysis published in *IEEE ECAI 2025*.

