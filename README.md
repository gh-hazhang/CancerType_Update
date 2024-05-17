# CancerType_Update

## Project Overview
This repository is a collaborative initiative to update cancer types in our biopharma RUO/IST data, which has been extracted from the data warehouse. The primary goal is to ensure that the missing values in the "cancerother" column are accurately filled. This effort is critical for our datasets for ongoing and future analyses.

## Getting Started

### Repository Structure
- **`df_all_ruo.csv`**: This is the primary CSV file that consolidates all RUO and IST data up to May 16, 2024. It contains critical fields such as the delivered report file name, Account name, SOW number, and file_creator. The "cancerother" column, specifically, requires updating to fill in missing cancer type information.
- **`data_extraction.ipynb`**: A Jupyter Notebook that details the data extraction process from the data warehouse. This script is used for pulling comprehensive RUO/IST data and includes instructions for locating `fc_dir` and `mbd_dir` (contains essential files like `msre_caller_mr_features.hdr.tsv` necessary for subsequent CSO caller run).
