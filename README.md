# Netflix Movies Analysis
![Netflix History](https://github.com/bridgetmensah/Investigating_Netflix_Data_w_Python/blob/main/redpopcorn.jpg)

This project investigates Netflix movies, focusing on films released in the 1990s. It uses Python to drive insights from a Netflix dataset, leveraging the Numpy, Pandas, and Matplotlib libraries to subset, filter, and visualize dataframes.

## Brief History


Netflix! What started in 1997 as a DVD rental service has since exploded into one of the largest entertainment and media companies. Working for a production company that specializes in nostalgic styles, I conducted research on movies released in the 1990s. Using Netflix data, I performed exploratory data analysis (EDA) to better understand this awesome movie decade.

## Main Objectives
1. **Find the most frequent movie duration** for films released in the 1990s.
2. **Identify the shortest action movie** in the dataset. We define a "short" movie as one with a duration of less than 90 minutes.

## The Data

The dataset used in this project is `netflix_data.csv`, which includes the following columns:

| Column          | Description                                  |
|-----------------|----------------------------------------------|
| show_id         | The ID of the show                           |
| type            | Type of show (e.g., movie, TV show)          |
| title           | Title of the show                            |
| director        | Director of the show                         |
| cast            | Cast members in the show                     |
| country         | Country of origin                            |
| date_added      | Date the show was added to Netflix           |
| release_year    | Year of the show’s Netflix release           |
| duration        | Duration of the show in minutes              |
| description     | Short description of the show                |
| genre           | Show genre (e.g., action, drama)             |

## Files in This Repository
1. **netflix_data.csv** - The dataset used for analysis.
2. **notebook.ipynb** - Jupyter Notebook containing the code that provides insights into the dataset and answers the main objectives.

## Technologies Used
- **Python**: For data processing and analysis
- **Numpy**: For numerical operations
- **Pandas**: For data manipulation and exploration
- **Matplotlib**: For data visualization



