# Clustering Antarctic Penguin Species

This project involves analyzing data about penguins in Antarctica. The data is available in CSV format as `penguins.csv`.

## Project Overview

You have been asked to support a team of researchers who have been collecting data about penguins in Antarctica. The data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network.

## Data

The dataset contains the following columns:
- `species`
- `island`
- `culmen_length_mm`
- `culmen_depth_mm`
- `flipper_length_mm`
- `body_mass_g`
- `sex`

## Notebooks

The main analysis is performed in the `main.ipynb` notebook. The notebook includes the following steps:
1. Loading the data from `penguins.csv`.
2. Performing preprocessing steps to create dummy variables.
3. Conducting K-means clustering on the dataset.
4. Creating a `stat_penguins` DataFrame with statistical summaries and saving it to `data/stat_penguins.csv`.

## Usage

To run the analysis, open the `main.ipynb` notebook in Jupyter Notebook or any compatible environment and execute the cells.

## Dependencies

- pandas
- matplotlib
- scikit-learn

## Acknowledgements

This project is from DataCamp. The data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network.

![Penguins](https://imgur.com/orZWHly.png)

Source: @allison_horst https://github.com/allisonhorst/penguins