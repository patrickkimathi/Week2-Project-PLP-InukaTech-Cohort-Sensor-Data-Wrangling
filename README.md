# Week 2 Sensor Data Reading Analysis
## Project Overview
This project demonstrates the process of cleaning, analyzing, and visualizing industrial sensor data using Python. 
The objective is to improve data quality by identifying and handling missing values, duplicate records, and outliers, 
allowing operational trends to be interpreted more accurately.
The project compares raw sensor readings with cleaned data to show how preprocessing improves decision-making in plant operations.

---
## Objectives
- Import and inspect sensor data.
- Identify data quality issues.
- Clean the dataset by handling:
  - Missing values
  - Duplicate records
  - Outliers
- Generate descriptive statistics.
- Visualize raw and cleaned sensor trends.
- Produce operational insights from the cleaned data.
---
## Dataset

**File:**
`week2_sensor_readings.csv`
The dataset contains timestamped sensor pressure readings collected from an industrial production environment.
---
## Technologies Used
- Python 3
- Pandas
- NumPy
- Matplotlib
---
## Project Workflow
### 1. Data Loading
The sensor dataset is imported into a Pandas DataFrame for analysis.
### 2. Data Exploration
The notebook examines:
- Dataset structure
- Data types
- Missing values
- Duplicate records
- Summary statistics

### 3. Data Cleaning
The following preprocessing steps are performed:
- Removal of duplicate records
- Handling missing values
- Detection and removal of outliers
- Data type validation
- Timestamp conversion

### 4. Data Analysis
The cleaned data is resampled into hourly averages to identify operational trends.

### 5. Data Visualization
A line chart compares:
- Raw Sensor Data
- Cleaned Sensor Data
This visualization highlights how data cleaning improves the accuracy of trend analysis.

---
## Key Findings
- Raw data contained missing values, duplicate records, and abnormal outliers.
- Outliers created misleading pressure spikes.
- Missing readings obscured the true operational trend.
- Cleaning revealed a consistent pressure increase during later operating hours.
- Clean data provides a more reliable basis for operational monitoring and maintenance planning.
--
## Business Impact
Using cleaned sensor data enables plant managers to:
- Detect genuine equipment issues earlier.
- Reduce false maintenance alarms.
- Improve predictive maintenance.
- Enhance operational reliability.
- Support data-driven decision-making.

---
## Output
The project produces:
- Cleaned sensor dataset
- Summary statistics
- Raw vs. Cleaned Trend chart
- Week 2 Insight Report (PDF)
---
## How to Run
1. Install the required libraries:
```bash
pip install pandas numpy matplotlib
```
2. Place the dataset (`week2_sensor_readings.csv`) in the project directory.
3. Open the Jupyter Notebook.
4. Run all cells sequentially.
---
## Project Structure
```
Week2/
│
├── Patrick Kariuki PLP Sensor Data Reading Analysis Week 2.ipynb
├── week2_sensor_readings.csv
├── Week2_Insight_Report_Patrick_Kariuki.pdf
└── README.md
```
---
## Author
**Patrick Kariuki**
Inuka Tech PLP Fellowship Data Analysis Program
Week 2 Assignment
---
## License
This project was developed for educational purposes as part of the PLP Data Science training program.
