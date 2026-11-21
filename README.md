# THIS PROJECT IS CREATED FOR PATIENT RECOVERY ANALYSIS IN HOSPITAL.
A simple Python data processing pipeline using pandas and numpy to generate, clean,
analyze, and group synthetic patient health records.
 
## FEATURE
### DATA GENERATION:
Simulates a 100-record patient dataset containing demographic
details, diagnoses, hospital stay durations, and recovery metric scores.
 ### DATA CLEANING:
 Handles missing data points programmatically by detecting null
observations and imputing entries using calculated averages.
 ### STATISTICAL ANALYSIS:
 Computes central metrics like average participant age alongside
overall minimum and maximum recovery thresholds.
### TARGETED FILTERING:
Utilizes logical masking arrays to segment and highlight vulnerable
senior populations showing low statistical recovery indications.
### AGGREGATION METRICES: 
Groups information dynamically by disease class to output
structured high-level performance and stay averages.

## HOW TO RUN: 
### 1.Prerequisites-
Ensure you have python 3.x installed on your system.This pipeline relies on the following external libraries:
* 'pandas'
* 'numpy'
### 2.Installation-
Install the necessary python packages using your configuration file:
'''bash
pip install -r requirement.txt
'''
### 3.Execution-
Run the main data pipeline script:
'''bash 
python Patient_recovery_analysis_in_hospital.py
'''
