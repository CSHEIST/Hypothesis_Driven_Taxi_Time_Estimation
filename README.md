# Hypothesis_Driven_Taxi_Time_Estimation
## Overview
This project analyzes Bangalore taxi trip data to estimate travel duration based on:
- Distance
- Source and Destination
- Traffic intensity (proxy via trip frequency)
- Time of day
- also based on crosses and junctions

## Objectives
- Identify most travelled routes
- Estimate travel duration statistically
- Analyze traffic intensity using trip counts
- Prepare foundation for dynamic rerouting system

## Dataset
Bangalore Taxi Dataset (Kaggle)

## Methods Used
- Data Cleaning
- Frequency-based Traffic Density Estimation
- GroupBy Route Analysis
- Hypothesis Testing
- Regression-ready structure

## How to Run

```bash
pip install -r requirements.txt
python src/analysis.py
