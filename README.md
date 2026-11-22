# Project 2: Exploratory Analysis of Air Pollution at RDU Airport

## Project Description

This project explores daily air pollutant concentrations at Raleigh-Durham International Airport (RDU) from 2018 through April 2020. The analysis focuses on carbon monoxide (CO), fine particulate matter (PM2.5), and ozone (O3).

The objective is to clean and summarize air quality data and visualize monthly and seasonal patterns in pollutant concentrations.

## Data Source

The data were obtained from the Environmental Protection Agency (EPA) air quality monitoring station at RDU Airport.

The project uses three datasets:
- `AQ_2018.csv` — 2018 observations
- `AQ_2019.csv` — 2019 observations
- `AQ_2020.csv` — January through April 2020 observations

## Repository Contents

- `AQ_2018.csv`, `AQ_2019.csv`, `AQ_2020.csv`: Raw air quality datasets.
- `Project2.Rmd`: R Markdown file containing data cleaning, summary statistics, visualizations, and interpretations.
- `Project2.docx`: Final Word report generated from the R Markdown file.
- `project 2.Rproj`: RStudio project file.
- `README.md`: Project overview and reproducibility instructions.

## Methods

The analysis includes cleaning daily pollutant measurements, handling duplicate and negative values, calculating annual minimum and maximum concentrations, and visualizing monthly pollutant patterns.

CO and ozone monthly means are displayed with 95% confidence intervals, while PM2.5 monthly averages are compared across years.

## Reproducibility

1. Download or clone this GitHub repository.
2. Open `project 2.Rproj` in RStudio.
3. Install the required R packages: `tidyverse`, `lubridate`, `knitr`, and `rmarkdown`.
4. Open `Project2.Rmd`.
5. Knit the R Markdown file to Word to reproduce the report.

## Author

Sia Gbondo-Tugbawa  
Duke University  
BIOSTAT 721  
Project 2  
November 2026
