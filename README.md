# Project 1: Nebraska Air Quality Analysis (February 2024 - March 2025)

## Project Overview
[cite_start]This project was commissioned by the **UNMC Water, Climate and Health Group** [cite: 2] to analyze air quality data across Nebraska. [cite_start]Since air quality is not a primary specialty of the UNMC working group, this analysis provides data-driven insights into how pollutants like **Volatile Organic Compounds (VOCs)** and **Particulate Matter (PM 2.5 and PM 10.0)** impact public health across the state[cite: 4, 6].

[cite_start]The primary objective is to identify air quality "hotspots," evaluate compliance with **National Ambient Air Quality Standards (NAAQS)**, and understand how environmental variables—such as temperature, humidity, and altitude—influence pollutant concentrations[cite: 9, 10].

---

## Objectives and Client Requests
[cite_start]The analysis addresses the following core questions and tasks[cite: 11]:
* [cite_start]**Top Pollutant Locations:** Identify the 5 locations in Nebraska with the highest mean and median concentrations of VOC, PM 2.5, and PM 10.0[cite: 12].
* [cite_start]**Peak Events:** Determine the dates and locations of maximum pollutant values and research potential causes for these occurrences[cite: 13, 14].
* [cite_start]**Environmental Correlation:** Analyze the effect of humidity and temperature categories on air quality[cite: 15].
* [cite_start]**AQI Risk Assessment:** Identify instances where Air Quality Index (AQI) levels reached "Unhealthy for Sensitive Populations" or higher for PM 2.5 and PM 10[cite: 20].
* [cite_start]**Altitude Impact (Bonus):** Evaluate if sensor altitude has a statistically relevant impact on air quality readings[cite: 23].

---

## Data Categories
[cite_start]The analysis utilizes specific categorizations provided by the client for environmental factors[cite: 16, 18]:

### Humidity Categories
| Category | Relative Humidity (%) |
| :--- | :--- |
| Low | < 50% |
| High | 50% - 80% |
| Very High | > 80% |

### Temperature Categories
| Category | Temperature Range (°F) |
| :--- | :--- |
| Below Freezing | < 32°F |
| Cool | 32°F - 50°F |
| Warm | 51°F - 70°F |
| Hot | > 70°F |

---

## Repository Contents
[cite_start]This repository contains all materials necessary to replicate the analysis[cite: 31, 38]:
* [cite_start]**`data/`**: Contains the raw CSV files from the AirPurple monitors used in the Python code[cite: 33, 35, 40].
* [cite_start]**`Air_Quality_Analysis.ipynb`**: The primary Python notebook containing the data processing, statistical computations, and visualizations[cite: 36, 37, 39].
* [cite_start]**`Scope_of_Work.pdf`**: A document defining the project tasks and group responsibilities[cite: 42].
* [cite_start]**`Annotated_Code_Document.pdf`**: A detailed explanation of the logic used in the Python script[cite: 43].
* [cite_start]**`Final_Report.pdf`**: The formal written summary of findings, methodology, and results intended for UNMC[cite: 44].
* [cite_start]**`README.md`**: This file, providing an overview and project description[cite: 41].

---

## Tools and Resources
* [cite_start]**Language:** Python 3.x [cite: 36]
* **Libraries:** Pandas, NumPy, Matplotlib/Seaborn
* [cite_start]**Data Sources:** [AirPurple Map](https://map.purpleair.com), Purple Air Community API, EPA Air Quality Tables, and [AirNow.gov](https://www.airnow.gov/)[cite: 26, 27, 28, 29].

---
[cite_start]*Submitted as part of Project #1 for the UNMC Water, Climate and Health initiative.* [cite: 5, 50]
