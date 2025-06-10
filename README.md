# ETL_Extraction_VivianKipsang

# Project Title: ETL Extract Lab

## Project Description:
This notebook demonstrates an **Incremental ETL (Extract, Transform, Load)** process using a simulated hospital visit dataset.  
It extracts only the **new or updated records** since the last extraction timestamp, which is tracked using a `last_extraction.txt` file.

##  Tools Used:
- **Python** (3.x)
- **pandas** – for data manipulation
- **Jupyter Notebook** – for running and documenting the workflow
- **VSCode** – for optional file management and GitHub integration

##  How to Reproduce:

### 1. Run the Notebook:
- Open the notebook in Jupyter or VSCode.
- Make sure `hospital_visits.csv` and `last_extraction.txt` are in the same folder.
- Run the notebook cells in order.

### 2. Data Source:
- The data is synthetically generated using Python.
- The CSV file `hospital_visits.csv` contains 2 months of simulated hospital check-in and check-out data.

---