# Population Analysis

This project is about analyzing the population data from the World Bank. The goal is to visualize the distribution of population across different countries and income groups.

## Dataset

The dataset used in this project is obtained from the World Bank's database( https://data.worldbank.org/indicator/SP.POP.TOTL) . 

## Requirements

The project is implemented in Python and uses the following libraries:
- numpy
- pandas
- matplotlib
- seaborn

## Project Description

The project involves several steps:

1. **Data Cleaning**: The dataset is cleaned by removing columns with all NaN values and filling missing values in numerical columns using interpolation.

2. **Data Visualization**: The cleaned data is then visualized using bar plots. The total population by country in 2022 is plotted. Then, the top and bottom 10 countries in 2022 by population are plotted.

3. **Data Merging**: Another dataset containing metadata of countries is merged with the original dataset on the 'country code' column.

4. **Grouped Visualization**: A subplot grid showing the top 10 countries over 2020, 2021, and 2022 grouped by income groups is created.

## Usage

To run the project, you need to have Python installed on your system. After that, you can install the necessary libraries using pip:
pip install numpy pandas matplotlib seaborn

## Contributing
Contributions are welcome. Please feel free to fork the project and create a pull request with your changes.


