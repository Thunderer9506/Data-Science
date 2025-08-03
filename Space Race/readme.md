# Space Race Data Analysis

## Project Overview
This project analyzes the history and trends of space missions from 1957 to 2024 using the Space Race dataset.  
The goal is to understand launch patterns, costs, organizational performance, and mission outcomes across decades of space exploration.

## Dataset
- **Source:** `all_space_mission_launches.csv`
- **Records:** 6,711
- **Features:**
  - Organisation: Launching organization
  - Location: Launch site
  - Datetime: Launch date and time
  - Details: Rocket and mission details
  - Rocket_Status: Active or retired
  - Price: Launch cost (in billion USD)
  - Mission_Status: Success or failure
  - Country: Extracted from the Location column
  - Year: Extracted from Datetime

## Technologies Used
- Python
- Pandas
- Matplotlib

## Data Cleaning Process
1. Removed unnecessary columns (e.g., `Unnamed: 0`).
2. Extracted `Country` from the `Location` column.
3. Converted `Datetime` to a proper datetime format (UTC).
4. Created a `Year` column from the datetime values.
5. Filled missing `Price` values using the mean for the corresponding year, and global mean if still missing.

## Exploratory Data Analysis
The analysis includes:
- Launches per year (globally and by country)
- Launches by organization
- Annual spending on rocket launches
- Spending by organization and country
- Active vs retired rockets
- Financial losses due to failed missions

## Key Insights
- The number of launches increased significantly during the Cold War, slowed down in the early 2000s, and has risen again with the growth of private space companies.
- The USA, Russia, and China lead in total launches.
- A spending spike in 1997 was driven by continued investment in space technology despite the Cold War’s end.
- Retired rockets outnumber active ones due to the historical use of expendable rocket designs.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/space-race-analysis.git
   cd space-race-analysis
2. Install dependencies:
   ```bash
    pip install pandas matplotlib
3. Place the dataset in the project directory.
4. Run the Jupyter Notebook:
   ```bash
    jupyter notebook
5. Open and execute `space_race_analysis.ipynb.`

Contact
For inquiries or collaboration, connect with me on LinkedIn.
