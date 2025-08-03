# Netflix Dataset Analysis

## Project Overview
This project analyzes the Netflix titles dataset, containing information about movies and TV shows available on the platform.  
The analysis focuses on content distribution, production trends, ratings, genres, and availability patterns.

## Dataset
- **Source:** `netflix_titles.csv`
- **Records:** 8,807 (after cleaning: 8,797)
- **Features:**
  - show_id: Unique identifier
  - type: Movie or TV Show
  - title: Name of the content
  - cast: Main cast members
  - country: Country of origin
  - date_added: Date the title was added to Netflix
  - release_year: Year of release
  - rating: Audience rating
  - duration: Duration (in minutes or seasons)
  - listed_in: Genre/category
  - description: Short description

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib

## Data Cleaning Process
1. Dropped the `director` column due to excessive missing values.
2. Removed rows with missing `date_added` values.
3. Filled remaining missing values with `'Unknown'`.
4. Converted `date_added` to datetime format for time-based analysis.

## Exploratory Data Analysis
- **Movies vs TV Shows:** Comparison of total counts.
- **Production by Country:** Top 20 countries producing content.
- **Content Additions Over Time:** Trends using `date_added`.
- **Release Year Trends:** Distribution of content release years.
- **Audience Ratings:** Count of titles in each rating category.
- **Genres & Categories:** Top categories by content count.

## Key Insights
- Movies significantly outnumber TV shows in the dataset.
- The United States dominates in content production, followed by India and the United Kingdom.
- A large volume of content was added to Netflix between 2018–2020.
- TV-MA and TV-14 are the most common ratings.
- Drama, International TV Shows, and Documentaries are the most frequent categories.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/netflix-analysis.git
   cd netflix-analysis
2. Install dependencies:
   ```bash
    pip install pandas numpy matplotlib
3. Place netflix_titles.csv in the project directory.

4. Run the Jupyter Notebook:
   ```bash
    jupyter notebook
5. Open and execute `netflix_analysis.ipynb.`

Contact
For inquiries or collaborations, connect with me on `LinkedIn`.
