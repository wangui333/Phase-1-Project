# Phase-1-Project
This is a data science repository project focused on analyzing aviation data using Python. It helps viewing accidents and preventing aviation accidents from happening frequently.
## Overview
For this project, i used data cleaning, imputation, analysis, and visualization to generate insights for the aviation data provided.  Aimed to identify key risk factors and trends happening.
## Business Understanding
- I am to determine which aircraft are the lowest risk for the company to start this new business.
- I must help to determine which aircraft to purchase using the new findings.
###  Stakeholder and key business questions:
- Aviation safety analysts
- What types of aircraft are most likely to have incidents?
- During which flight phases do most serious accidents occur?
## Data Understanding and Analysis
### Source of Data:
In the data folder AviationData from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.
### Description of Data:
80,000+ rows and multiple features including:
 -     'Event.Id', 'Investigation.Type', 'Accident.Number', 'Event.Date',
       'Location', 'Country', 'Latitude', 'Longitude', 'Airport.Code',
       'Airport.Name', 'Injury.Severity', 'Aircraft.damage',
       'Aircraft.Category', 'Registration.Number', 'Make', 'Model',
       'Amateur.Built', 'Number.of.Engines', 'Engine.Type', 'FAR.Description',
       'Schedule', 'Purpose.of.flight', 'Air.carrier', 'Total.Fatal.Injuries',
       'Total.Serious.Injuries', 'Total.Minor.Injuries', 'Total.Uninjured',
       'Weather.Condition', 'Broad.phase.of.flight', 'Report.Status',
       'Publication.Date'
###  visualizations
1. **Boxplot of Total Serious Injuries**
    - Shows distribution and outliers of serious injury cases across all events.

2. **Bar Plot: Accidents by Phase of Flight**
    - Highlights that most incidents occur during landing and approach phases.

3. **Scatter Plot: Serious Injuries vs. Flight Phase**
    -  Correlates injury severity with flight phases.
## Conclusion
  - Most accidents happen during landing and approach
  - Some location have higher incidents count
##  Commit History

Project developed over multiple stages:
  - Data cleaning
  - Imputation
  - EDA
  - Visualizations
  - Final conclusions
## Organization
aviation-data-analysis
 1. - AviationData.csv
    - Datacleaning.csv
 2. Aviation_insights_slides.pdf
 3.  - .gitignore
      - README.md
## Notebooks
  - Notebook - Phase 1 Project.ipynb
  - PowerPoint Notebook - Phase 1 Project.pdf 
## License
This project is licensed under the MIT License.


