This project is created for patient recovery analysis in hospital.
A simple Python data processing pipeline using pandas and numpy to generate, clean,
analyze, and group synthetic patient health records.
Features
Data Generation: Simulates a 100-record patient dataset containing demographic
details, diagnoses, hospital stay durations, and recovery metric scores.
Data Cleaning: Handles missing data points programmatically by detecting null
observations and imputing entries using calculated averages.
Statistical Analysis: Computes central metrics like average participant age alongside
overall minimum and maximum recovery thresholds.
Targeted Filtering: Utilizes logical masking arrays to segment and highlight vulnerable
senior populations showing low statistical recovery indications.
Aggregation Metrics: Groups information dynamically by disease class to output
structured high-level performance and stay averages.
