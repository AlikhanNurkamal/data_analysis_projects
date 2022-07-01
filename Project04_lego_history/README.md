This is an analysis of the history of LEGO sets releases and sales. The project is based on the dataset and investigation questions from DataCamp unguided project called "Exploring the History of Lego".

The main goal of the project was to analyze the popularity of Star Wars themed LEGO sets, namely: "uncovering the percentage of all licensed sets that are Star Wars themed" and "which year Star Wars was not the most popular set".

There are two datasets in this project to work with:
1. ***lego_sets.csv***
* ***set_num:*** A code that is unique to each set in the dataset. This column is very critical, so no missing values should be.
* ***name:*** A name for every set in the dataset.
* ***year:*** The year of the release of the set.
* ***num_parts:*** The number of parts contained in the set. This column is not as important as others.
* ***theme_name:*** The name of the sub-theme of the set.
* ***parent_theme:*** The name of the parent theme to which the set belong. This MUST match the "name" columns in the following dataset.

2. ***parent_themes.csv***
* ***id:*** A code that is unique to every theme.
* ***name:*** The name of the parent theme.
* ***is_licensed:*** The column that specifies whether a theme is licensed or not.
