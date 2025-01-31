# Netflix Movie Duration Analysis

## Project Overview
This project explores trends in Netflix movie durations over the past decade, identifying patterns in genres and their potential impact on average movie lengths. By analyzing data from Netflix's movie catalog, this project dives into the changing nature of movie durations, offering insights into how the entertainment landscape has evolved.
The analysis involves filtering data, visualizing trends, and investigating the relationship between movie length and genre. The project also touches on exploratory data analysis (EDA) and data visualization techniques using Python libraries such as pandas and matplotlib.

## Key Insights
* Trend of shorter movies: The analysis reveals a decline in movie duration over the years, with a noticeable concentration of shorter movies in the past decade.
* Genre influence: Non-typical genres like Children’s Movies, Documentaries, and Stand-Up Specials are responsible for shorter movie durations compared to traditional blockbuster genres.

## Skills and Tools
* Pandas: Efficient data manipulation, filtering, and cleaning.
* Matplotlib: Data visualization, including line plots and scatter plots.
* Exploratory Data Analysis (EDA): Initial data exploration, trend identification, and hypothesis generation.
* Data Wrangling: Handling missing data, managing different data types, and creating meaningful subsets.

## Project Workflow
1. Data Loading: The dataset was loaded from a CSV file containing information about Netflix movies and TV shows. This raw data was filtered to focus on movies only.
2. Exploratory Data Analysis (EDA): We performed an initial inspection of the data, identified key features, and explored trends in movie durations over time. A line plot and scatter plot were used to visualize these trends.
3. Filtering and Subsetting: Only relevant columns (movie title, country, genre, release year, and duration) were kept. Additionally, the dataset was filtered to focus on movies, excluding TV shows.
4. Genre Analysis: A deeper dive into genres like Children's Movies, Documentaries, and Stand-Up led to identifying the impact of these genres on the overall distribution of movie durations.
5. Visualization: Multiple visualizations were created to represent the relationship between movie release year and duration, with color-coded genres for better clarity.
6. Next Steps: Future analyses could involve statistical modeling (e.g., regression analysis) to quantify the impact of genre on movie duration and confirm the trends observed in the EDA.

## Getting Started
To run the analysis locally, follow these steps:
1. Clone the Repository
   
git clone https://github.com/yourusername/netflix-movie-duration-analysis.git

cd netflix-movie-duration-analysis
3. Install Dependencies
This project requires Python and the following libraries:
* pandas
* matplotlib

You can install the dependencies using pip:

pip install -r requirements.txt
3. Load the Data
Make sure the data file (netflix_data.csv) is available in the datasets/ directory. If it is not included, you can download it from the relevant source (such as Kaggle or other open datasets).
4. Run the Notebook
After setting up your environment, open the Jupyter notebook (netflix_movie_duration_analysis.ipynb) and run the cells to explore the data and generate the visualizations.

## Conclusion
This project serves as an introduction to data exploration and analysis using Python. It demonstrates techniques for handling, visualizing, and interpreting real-world datasets, and it provides insights into how movie durations have changed over time, with a focus on the influence of different genres.

## Future Work
* Applying statistical analysis, such as regression, to validate the trends.
* Exploring the impact of other factors (e.g., production budget, director, cast) on movie durations.
* Investigating TV shows and comparing their trends to movies.

