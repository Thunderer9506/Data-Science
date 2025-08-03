# 🚀 Space Race Data Analysis

## 📌 Project Overview
This project explores the history and trends of space missions from **1957 to 2024** using the **Space Race dataset**.  
It analyzes launches across countries, organizations, costs, and mission outcomes to uncover insights about global space exploration.

## 📂 Dataset
- **Source:** `all_space_mission_launches.csv`
- **Rows:** 6,711
- **Columns:** 9
- **Key Features:**
  - `Organisation`: Launching organization
  - `Location`: Launch site
  - `Datetime`: Launch date and time
  - `Details`: Rocket & mission details
  - `Rocket_Status`: Active or retired
  - `Price`: Launch cost (in Billion $)
  - `Mission_Status`: Success/Failure
  - `Country`: Extracted from Location
  - `Year`: Extracted from Datetime

## 🛠 Dependencies
```python
pandas
matplotlib
