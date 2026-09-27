# train-route-enquiry-python
Python-based Train Schedule Analysis and Interactive Route Enquiry System developed as an ongoing internship project at Sysslan IT Solution
# Train Schedule Analysis and Interactive Route Enquiry System Using Python

## 📌 Project Overview

This project is being developed as part of an internship at Sysslan IT Solutions.

The project focuses on analysing train schedule data using Python and developing an interactive route enquiry system.

The system analyses train schedules, performs data quality checks, generates visualisations, and allows users to search for direct trains between two stations.

## 🎯 Objectives

- Analyse train schedule data
- Identify starting and ending stations
- Calculate the number of stops for each train
- Calculate journey durations
- Classify routes based on journey duration
- Perform data quality checks
- Identify high-traffic stations
- Create pivot tables and comparative visualisations
- Develop an interactive route enquiry system

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## 📊 Project Levels

### Level 1 – Basic Data Review

- Dataset overview
- Train start and end stations
- Number of stops
- Maximum and minimum stops

### Level 2 – Simple Data Processing

- Time standardisation
- Journey duration calculation
- Route classification
- Station frequency analysis

### Level 3 – Data Quality Checks

- Missing-value checking
- Duplicate checking
- Station-order verification
- Dataset verification

### Level 4 – Basic Analysis & Visualization

- Average journey duration
- High-traffic stations
- Data visualisations
- Analytical observations

### Level 5 – Advanced Analysis & Visualization

- Pivot tables
- Cross-tabulation
- Comparative charts
- Advanced insights

### Level 6 – Interactive Route Enquiry System

The system allows users to enter:

- Source station
- Destination station

The system then displays available direct trains along with:

- Train number
- Source station
- Departure time
- Destination station
- Arrival time
- Estimated journey duration

## 🚆 Sample System Output

| Train No | Source | Departure | Destination | Arrival | Journey Duration |
|----------|--------|-----------|-------------|---------|------------------|
| Example | Station A | 08:30 | Station B | 14:45 | 6 hours 15 minutes |

## 📁 Project Structure

```text
Train-Schedule-Analysis/
│
├── Train_Schedule_Analysis.ipynb
├── Dataset1.csv
├── README.md
└── requirements.txt
