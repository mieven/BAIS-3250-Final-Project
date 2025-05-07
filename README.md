# BAIS-3250-Final-Project

Behind the Numbers: Do Ratings, Runtimes, and Star Power Predict Box Office Success? 

## Purpose of Project
The main point of this project is to investigate whether critically acclaimed and highly rated movies actually perform better at the box office compared to average-rated, widely promoted films. It aims to explore the relationship between digital ratings from platforms like IMDb, Rotten Tomatoes, and Metacritic and a film’s financial success, uncovering whether ratings are reliable indicators or if other factors—like marketing and budget—play a more significant role.

## Websites Used
| Title | Link |
| ------ | ------ |
| Scraped Website | [Website Scraped][PlDb] |
| Kaggle Dataset | [Kaggle Site][PlGh] |

   [PlDb]: <https://www.movierankings.net/README.md>
   [PlGh]: <https://www.kaggle.com/datasets/dahvid/movie-budgets-and-revenues/README.md>

## Data Folder
The "Data" folder contains a CSV file with detailed movie data, including budgets, box office earnings, and ratings from Rotten Tomatoes, IMDb, and Metacritic. The Jupyter notebook explores how these factors relate to box office performance through data cleaning, visualizations, and regression analysis. A data dictionary outlines all variables, offering a clear reference for analyzing the impact of ratings, genre, and production details on a film's commercial and critical success.

### Data Dictionary
The data dictionary provides a comprehensive view of movies by combining financial data—such as budget, domestic gross, and worldwide earnings—with critic and audience ratings from major platforms like Rotten Tomatoes, IMDb, and Metacritic. It also includes descriptive details such as genre, runtime, studio, director, and awards, offering rich context for analysis. This allows for in-depth exploration of how different factors influence a movie’s critical reception and commercial success.


### Kaggle Dataset (movie_budgets_and_revenues)
This is the dataset taken from Kaggle that we then used to merge with our scraped data. It includes the movies release date, movie name, movie budget, and both domestic and worldwide gross. We use the movie name/title between our scraped data and Kaggle dataset to merge them together and create Final Movies.


### Final Movies File
This dataset is our full scraped CSV file merged with out Kaggle dataset that contains detailed information on a wide range of movies, including release dates, budgets, box office earnings (domestic and worldwide), runtimes, and genres. It also includes critical and audience ratings from Rotten Tomatoes, IMDb, and Metacritic, as well as metadata such as studios, directors, and award details. This rich combination of financial and descriptive data allows for in-depth analysis of what factors drive a movie’s commercial and critical success.


### Scraping Code (Movie_Scraping_Code)
This Jupyter notebook contains the code used to scrape movie ratings from the chosen website and integrates that data with the Kaggle movie dataset. It streamlines the process of combining critical scores with financial metrics, forming the foundation for deeper analysis. This merged dataset enables more accurate and comprehensive insights into box office performance.


### Jupyter Notebook (Final Project Analysis)
Our Jupyter notebook analyzes the relationship between movie ratings and box office performance using data from multiple sources. It includes data cleaning, exploratory visualizations, and regression models to evaluate whether higher ratings predict greater revenue and many other analysis questions. The notebook aims to uncover key factors that influence a film’s commercial success beyond just critical acclaim.


## Proposed Analysis Questions Folder
Our analysis questions explore how factors like ratings, genre, budget, studio, and runtime influence a movie’s box office performance. It aims to uncover whether high ratings consistently drive greater revenue, how genre and production decisions impact financial outcomes, and what role critical acclaim or awards play in a film's success. Additionally, the project examines long-term trends in movie characteristics, such as runtime and studio dominance, across different decades.

## Analysis Folder
Houses a report investigates the relationship between critical acclaim and monetary success in the film industry by analyzing factors like runtime, box office earnings, critic ratings, and the presence of award-winning talent. The report focuses on 3 main analysis quesitons: Has the average runtime of movies changed over different decades and do movies with longer runtimes tend to have higher or lower box office earnings? What is the correlation between movie ratings on platforms like IMDb, Metacritic, and Rotten Tomatoes and box office performance? Does the presence of award-winning actors/directors influence box office or total score?
