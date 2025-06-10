# ETL_Extraction_VivianKipsang

# Project Title: ETL Extract Lab

## Project Description:
This notebook demonstrates an **Incremental ETL (Extract, Transform, Load)** process using a simulated hospital visit dataset.  
It extracts only the **new or updated records** since the last extraction timestamp, which is tracked using a `last_extraction.txt` file.

This project follows the lab manual Practicing Extraction in ETL:
1. Choose (or generate) a realistic dataset.
2. Implement:
    - Full Extraction
     - Incremental Extraction
3. Document each step clearly in a Jupyter Notebook.
4. Upload your work to GitHub for submission.


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

## Conclusion 
This project successfully implemented an incremental data extraction process using Python and pandas, simulating a real-world ETL workflow. By tracking timestamps via a simple last_extraction.txt file, the solution efficiently filtered and extracted only new or updated records from a larger dataset. 

---