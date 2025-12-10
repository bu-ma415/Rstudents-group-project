# Rstudents Group Project

This project analyzes public health inspection data from four major U.S. cities to identify patterns in food safety violations. The repository is organized to keep data, source code, and final outputs clearly separated.

## Data Sources
Food establishment inspection datasets used in this project:

- Boston: https://data.boston.gov/dataset/food-establishment-inspections/resource/4582bec6-2b4f-4f9e-bc55-cbaa73117f4c  
- New York City: https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j/about_data  
- Chicago: https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5/about_data  
- San Francisco: https://data.sfgov.org/Health-and-Social-Services/Health-Inspection-Scores-2016-2019-/pyih-qa8i/about_data  

## Repository Structure

| File/Folder            | Purpose                                                                                                                           | Status                                              |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------|
| `data/`                | Raw datasets from all four cities and the merged cleaned dataset (`inspections_clean.csv`).                                       | Ignored by Git due to size.                         |
| `Rstudentsproject.Rmd` | Main analysis notebook containing all R code for EDA, modeling, and visualization. Serves as the full reproducible script.        | Tracked by Git.                                      |
| `Report.md`            | Final written report with introduction, analysis summary, and conclusions.                                                        | Tracked by Git.                                      |
| `data_cleaning.Rmd`        | Script used for initial cleaning and merging (e.g., ``).                                                                          | Tracked by Git.                                      |
| `report_images/`              | Exported plots used in the final report and presentation.                                                                         | Tracked by Git.                                      |

## Research Questions

### Main Question
- What are the most common food safety violations across each city?

### Individual Questions
- **Gian:** How do violations vary geographically within each city? Which zip codes show the highest violation counts?  
- **Seun:**  
  1. Do certain restaurant categories (e.g., Pizza, Sushi, Coffee Shop) receive specific types of violations more frequently?  
  2. How do violation types and severity differ between complaint-driven vs. routine inspections?  
- **Niki:** Which months and seasons show the highest number of violations within each city and overall?  
- **Arohi:** How have the most frequent violations changed over time (e.g., 2015 vs. 2020), and what may explain these trends?
