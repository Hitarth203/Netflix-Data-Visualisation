# Netflix Data Visualisation

This project explores and visualizes Netflix content data using Python, Pandas, and Matplotlib. It provides insights into the types of content on Netflix, distribution by country, duration of movies, release trends, and more.

## Dataset

The dataset used in this project is `netflix_titles_data.xlsx`, which contains information about Netflix titles such as:
- Show ID
- Type (Movie or TV Show)
- Title
- Director, Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre (Listed In)
- Description

## Visualizations

1. **Number of Movies vs TV Shows**
   - A bar chart showing the count of Movies and TV Shows available on Netflix.
   -  `movies_tvshows.png`

2. **Content Ratings Distribution**
   - A pie chart grouped to show rating proportions.
   -  `content_ratings_pie.png`

3. **Movie Duration Distribution**
   - Histogram showing how long most movies are.
   -  `movies_duration_hist.png`

4. **Release Year Trend**
   - A scatter plot showing how many shows were released per year.
   -  `release_png.png`

5. **Top 10 Countries by Number of Shows**
   - A horizontal bar chart showing which countries have the most Netflix content.
   -  `top10_countries.png`

6. **Content Released Over Years (Line Plot)**
   - Comparison of TV Shows and Movies released per year.
   -  `movies_tv_shows_comparison.png`

##  Files

- `netflix_titles_data.xlsx` — Raw dataset.
- `Netflix_Content_Analytics.ipynb` — Main Jupyter Notebook with code and visualizations.
- Image files — All charts and plots saved during analysis.

##  Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

##  How to Run

1. Clone this repository.
2. Open `Netflix_Content_Analytics.ipynb` in Jupyter Notebook.
3. Ensure you have the required libraries:
   ```bash
   pip install pandas matplotlib openpyxl
