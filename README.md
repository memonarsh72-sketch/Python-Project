# Assessment Analysis Project

This project analyses assessment and course data using **Excel, SQL, Python and Power BI**.

## Project Structure


data/raw/          → Original CSV files
excel/             → Excel analysis
sql/               → SQL setup and queries
python/            → Python analysis
powerbi/            → Power BI dashboard
outputs/            → Charts, summaries and SQL results

Tools Used
Excel: Data cleaning, formulas, PivotTable and chart

SQL (SQLite 3): Database setup and analytical queries

Python: pandas and matplotlib for analysis and charts

Power BI: Dashboard, DAX measures and interactive filtering

Data Checks
Original assessment rows: 13

Clean assessment rows: 12

Course rows: 4

Duplicate row removed

Course IDs checked for unmatched records

Main Outputs
outputs/clean_data.csv

outputs/python_summary.csv

outputs/python_chart.png

outputs/powerbi_dashboard.png

SQL results in outputs/sql/

SQL Execution
Run sql/setup.sql first, followed by sql/queries.sql.

Power BI Refresh
The report uses CSV files from data/raw/. If the project is moved,
update the file paths in Power Query and refresh the report.

