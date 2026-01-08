# Emergency Department Flow Optimization – UCSD Health (Capstone)

## Overview
This project develops a discrete-event simulation model to analyze patient flow through a large academic medical center’s Emergency Department (ED). The goal is to identify operational interventions that reduce ED congestion, hallway bed usage, and prolonged EDIP stays without increasing bed capacity.

## Problem Context
Rising ED arrivals and higher-acuity cases, combined with constrained inpatient bed availability, have led to prolonged boarding of admitted patients in EDIP and hallway beds. These downstream bottlenecks negatively impact wait times, staff workload, and patient experience.

## Methodology
- Discrete-event simulation built in Python
- Modeled hourly/day-of-week arrival patterns
- Severity-based triage using Emergency Severity Index (ESI 1–5)
- Explicit modeling of ED beds, EDIP beds, and inpatient hospital beds
- Dynamic bed competition based on discharge-driven capacity

## Interventions Tested
1. Reduced inpatient LOS for a subset of SNF-bound patients  
2. Shifted discharge timing earlier in the day to free beds during ED peak hours  
3. Diverted low-acuity (ESI 4–5) patients to urgent care  

## Key Results
- Reduced simulated EDIP volumes by ~30–40%
- Shortened long-tail EDIP length-of-stay distributions
- Decreased reliance on hallway and surge beds
- Identified discharge timing as a higher-impact lever than demand diversion alone

## Tools & Technologies
- Python (SimPy, pandas, NumPy)
- Jupyter Notebooks
- Discrete-event simulation
- Data-driven scenario analysis

## Disclaimer
This project is based on de-identified, aggregated data and is presented at a high level to preserve confidentiality. Results are for academic and illustrative purposes only.

## Author
Master’s in Business Analytics – UC San Diego (Rady School of Management)  - Preetish Parikh
