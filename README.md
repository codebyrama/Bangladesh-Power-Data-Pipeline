# Bangladesh-Power-Data-Pipeline
**Authors:** Md. Ikrama Hossain, Tasnia Nafs, Sakif Yeaser

This repository hosts the Python-based scraping and preprocessing pipeline developed to construct a multi-year dataset of daily electricity demand, generation, load shedding, and external conditions in Bangladesh. The scripts automate the retrieval of daily reports from the **Bangladesh Power Development Board (BPDB)** digital archive, parse structured tables from PDFs, clean and validate records, impute missing values, enrich features (holidays, temperature, temporal attributes), and export the data into machine-readable formats.

* The **dataset** is documented in the article:
  *Md. I. Hossain, T. Nafs, S. Yeaser, A. Newaz. Multi-Year Dataset on Daily Electricity Demand, Generation, Load Shedding, and External Conditions in Bangladesh.*
  *Data in Brief*, 2025 (under review).

* The **analysis of deep learning models** built on this dataset is published in:
  *S. Yeaser, T. Nafs, Md. I. Hossain. Comparative Analysis of Deep Learning Models for Long-Term Electricity Demand Forecasting in Bangladesh Using Web-Scraped Data.*
  In: *2025 17th International Conference on Electronics, Computers and Artificial Intelligence (ECAI)*, IEEE, Târgoviște, Romania, 26–27 June 2025, pp. 1–7.
  DOI: [10.1109/ECAI65401.2025.11095479](https://doi.org/10.1109/ECAI65401.2025.11095479)

This repository ensures reproducibility of the dataset creation process and provides a reusable framework for updating with new BPDB reports or adapting to similar regional energy contexts.
