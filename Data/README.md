## Data Dictionary
The data dictionary provides a comprehensive view of movies by combining financial data—such as budget, domestic gross, and worldwide earnings—with critic and audience ratings from major platforms like Rotten Tomatoes, IMDb, and Metacritic. It also includes descriptive details such as genre, runtime, studio, director, and awards, offering rich context for analysis. This allows for in-depth exploration of how different factors influence a movie’s critical reception and commercial success.


### Kaggle Dataset (movie_budgets_and_revenues)
This is the dataset taken from Kaggle that we then used to merge with our scraped data. It includes the movies release date, movie name, movie budget, and both domestic and worldwide gross. We use the movie name/title between our scraped data and Kaggle dataset to merge them together and create Final Movies.


## Final Movies File
This dataset is our full scraped csv file that contains detailed information on a wide range of movies, including release dates, budgets, box office earnings (domestic and worldwide), runtimes, and genres. It also includes critical and audience ratings from Rotten Tomatoes, IMDb, and Metacritic, as well as metadata such as studios, directors, and award details. This rich combination of financial and descriptive data allows for in-depth analysis of what factors drive a movie’s commercial and critical success.


## Scraping Code (Movie_Scraping_Code)
This Jupyter notebook contains the code used to scrape movie ratings from the chosen website and integrates that data with the Kaggle movie dataset. It streamlines the process of combining critical scores with financial metrics, forming the foundation for deeper analysis. This merged dataset enables more accurate and comprehensive insights into box office performance.


## Jupyter Notebook (Final Project Analysis)
Our Jupyter notebook analyzes the relationship between movie ratings and box office performance using data from multiple sources. It includes data cleaning, exploratory visualizations, and regression models to evaluate whether higher ratings predict greater revenue and many other analysis questions. The notebook aims to uncover key factors that influence a film’s commercial success beyond just critical acclaim.
