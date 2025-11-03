# CS-Assissment
## Energy Access Analysis in R

This project analyzes global energy access data, focusing on electricity and clean cooking fuel accessibility for selected countries (India and China).  
It uses R for data processing, visualization, and comparative analysis of access trends, annual improvements, and correlations between electricity and clean fuel access rates.

## Description

The script processes and visualizes data from World Bank on the number of people with and without access to electricity and clean cooking fuels.  

It provides:
- Calculations of electricity access rates and clean fuel usage ratios  
- Trend visualizations over time  
- Yearly improvement comparisons  
- Correlation analysis between electricity and clean fuel access  


## Features

- Data cleaning and transformation with tidyverse
- Custom functions for calculating access percentages and ratios
- Trend and improvement visualization with ggplot2
- Comparative plots between countries (India, China)
- Correlation analysis between electricity and clean fuel access rates


## Requirements

Required R packages (automatically installed if missing):
- `pacman`
- `tidyverse`
- `kableExtra`
- `gridExtra`

## Project Structure
energy-access-analysis/
├── Energy_Access_Analysis.R                  
├── Energy_Access_Analysis.qmd                
├── Number_of_people_with_and_without_energy_access.csv 
├── README.md                                
├── Energy_Access_Analysis.html               
└── html_derived_files/                      
