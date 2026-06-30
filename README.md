# Netflix Content Visualization

## Project Overview
This project analyzes Netflix content using Python to explore patterns in movies and TV shows available on the platform. The notebook includes data cleaning, exploratory data analysis, and visualizations to better understand Netflix’s content library.

## Objective
The main objective of this project is to perform exploratory data analysis on the Netflix dataset and identify trends in:
- Content type
- Genres
- Ratings
- Countries
- Release trends
- Duration

## Dataset
- **Dataset Name:** Netflix Titles
- **File Used:** `netflix_titles.csv`
- **Source:** Kaggle

The dataset contains details such as title, director, cast, country, date added, release year, rating, duration, and listed genres.

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed
The following steps were completed in this project:
- Imported and inspected the dataset
- Cleaned missing values and formatted columns
- Analyzed content type distribution
- Visualized top genres on Netflix
- Studied rating distribution
- Explored top content-producing countries
- Examined content added over the years
- Analyzed movie duration distribution

## Key Insights
- Movies are more common than TV Shows in the dataset.
- Some genres appear much more frequently than others.
- Netflix includes a large number of mature and teen-oriented titles.
- The United States contributes the highest amount of content.
- Netflix expanded its library more heavily in recent years.
- Most movies fall within a typical feature-length runtime range.

## Project Structure
```text
Netflix-Content-Visualization/
│
├── data/
│   └── netflix_titles.csv
├── notebooks/
│   └── netflix_analysis.ipynb
├── images/
│   └── visualizations
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run the Project
1. Clone the repository.
2. Open the project folder in VS Code or Jupyter Notebook.
3. Create and activate a virtual environment.
4. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
5. Open the notebook and run all cells step by step.

## Conclusion
This project provides a clear overview of Netflix’s catalog through data analysis and visualization. It highlights the dominance of movies, popular genres, common ratings, leading countries, and content growth trends over time.

## Author
**Shravani**
