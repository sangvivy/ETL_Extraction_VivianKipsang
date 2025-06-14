# ETL_Extraction_VivianKipsang

# Project Title: ETL Extract & Transformation Lab

## Project Description:
This notebook demonstrates an **Incremental ETL (Extract, Transform, Load)** process using a simulated hospital visit dataset.  
It extracts only the **new or updated records** since the last extraction timestamp, which is tracked using a `last_extraction.txt` file.

This project follows the lab manual Practicing Extraction in ETL:
1. Choose (or generate) a realistic dataset.
2. Implement:
    - Full Extraction
     - Incremental Extraction

### Transformation Process

After extraction, both full and incremental datasets undergo several transformations to prepare the data for analysis:

1. **Cleaning:**  
   - Removed duplicate records.
   - Handled missing values by filling missing `cost` values with the column's median.

2. **Enrichment:**  
   - Calculated `visit_duration_minutes` based on visit start time and check-out time.

3. **Structural:**  
   - Standardized date formats for `visit_date` and `check_out_time` to ensure consistency (`YYYY-MM-DD` and `YYYY-MM-DD HH:MM:SS` formats).

The final transformed datasets are saved as:

- `transformed_full.csv`
- `transformed_incremental.csv`

3. Document each step clearly in a Jupyter Notebook.
4. Upload your work to GitHub for submission.

##  Tools Used:
- **Python** (3.12.4)
- **pandas** – for data manipulation
- **Jupyter Notebook** – for running and documenting the workflow
- **VSCode** – for optional file management and GitHub integration


##  How to Reproduce:

### 1. Run the Notebook:
- Open the notebook in Jupyter or VSCode.
- Make sure `hospital_visits_apr_may.csv` and `hospital_visits_apr_may.csv` are in the same folder.
- Run the notebook cells in order.

### 2. Data Source:
- The data is synthetically generated using Python.
- The CSV file `hospital_visits_apr_may.csv` contains 2 months of simulated hospital check-in and check-out data.

## Conclusion 
This project successfully implemented an incremental data extraction process using Python and pandas, simulating a real-world ETL workflow.
By tracking timestamps via a simple last_extraction.txt file, the solution efficiently filtered and extracted only new or updated records from a larger dataset.

Additionally, multiple data transformation steps were applied to prepare the data for further analysis:

- Cleaning to remove duplicates and handle missing values.

- Enrichment by calculating visit duration for each hospital visit.

- Structural formatting to standardize date and time fields.

- The final result is a clean, enriched, and analysis-ready dataset stored as both full and incremental transformed CSV files.



---

