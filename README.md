# Hospital Patient Care Analytics Pipeline

## Data Engineering Case Study

### Objective
Build a beginner-friendly end-to-end data engineering pipeline for a multi-specialty hospital.

### Workflow
**CSV → Jupyter/Python → Inspect → Clean → Transform → Validate → Analyze → Export → SQL Database → SQL Analysis**

### Datasets
- `patients.csv`
- `appointments.csv`
- `lab_reports.csv`
- `wearable_data.csv`
- `consultations.csv`

The included data is synthetic educational data and does not contain real patient information.

### Tools
Python, Pandas, NumPy, Matplotlib, Seaborn and SQLite.

### SQL connection
The notebook cleans and transforms the data in Python, exports the processed data, loads it into a SQL database, and then runs SQL queries on the stored data. SQLite is used so the notebook can run without installing a database server. The same SQL logic can be adapted to MySQL.

### Beginner explanation
The main idea I learned is that data engineering is not only analysis. The complete process is to collect data, inspect it, clean it, transform it, validate it, store it in a database and then analyze the stored data.
