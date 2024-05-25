# Netflix Movie Duration Analysis

## Overview
This project aims to analyze the duration of movies available on Netflix to investigate whether there's a trend of decreasing movie lengths over time. The analysis utilizes a dataset (`netflix_data.csv`) containing information about various shows available on Netflix, including their duration, release year, genre, and other relevant details.

## Dataset Description
The dataset contains the following columns:

- `show_id`: The ID of the show
- `type`: Type of show (e.g., Movie, TV Show)
- `title`: Title of the show
- `director`: Director of the show
- `cast`: Cast of the show
- `country`: Country of origin
- `date_added`: Date added to Netflix
- `release_year`: Year of Netflix release
- `duration`: Duration of the show in minutes
- `description`: Description of the show
- `genre`: Show genre

## Analysis Steps
1. **Loading the Data**: The CSV file (`netflix_data.csv`) is loaded into a Pandas DataFrame.
2. **Filtering TV Shows**: Only movies are considered for this analysis, so TV shows are filtered out.
3. **Subsetting Netflix Movies**: Relevant columns such as title, country, genre, release year, and duration are selected for further analysis.
4. **Identifying Short Movies**: Movies with a duration of less than 60 minutes are filtered out.
5. **Assigning Colors to Genre Groups**: Colors are assigned to different genre groups for visualization purposes.
6. **Creating Scatter Plot**: A scatter plot is generated to visualize the relationship between movie duration and year of release.
7. **Answering the Question**: Based on the analysis, the question of whether movie durations are decreasing over time is addressed.

## Conclusion
The initial analysis suggests that there are indeed movies on Netflix with durations shorter than 60 minutes. However, further investigation is required to determine if there's a significant trend of decreasing movie lengths over time. Factors such as changing audience preferences, production budgets, and the rise of streaming platforms may contribute to any observed trends.

## Future Work
Future iterations of this analysis could include:
- Statistical tests to determine the significance of any observed trends.
- Exploring the impact of movie duration on viewer engagement or ratings.
- Incorporating additional datasets or external factors that may influence movie lengths.
