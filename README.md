# Antimicrobial Resistance  & Antibiotic Use in the U.S. (2019–2023) Analysis

## Project Overview
This project analyzes the emergence and evolution of antimicrobial resistance (AMR) across the United States by integrating CDC antimicrobial resistance surveillance data, outpatient antibiotic prescribing data, and U.S. Census population estimates.

The analysis focuses on identifying:
- Pathogen-specific resistance trends
- Geographic hotspots of AMR
- Relationships between antibiotic use and resistance
- Population-normalized burden of AMR
- Potential future AMR hotspots using forecasting

This project was completed as a final course project and is intended to demonstrate applied data analysis, public health reasoning, and visualization skills.

---

## Research Questions
1. How have AMR rates changed across U.S. states over time?
2. Which pathogens (MRSA, CRE, ESBL, VRE, MDR *Acinetobacter*) show the most significant trends?
3. Is there a relationship between outpatient antibiotic prescribing and AMR prevalence?
4. How does population normalization affect interpretation of AMR burden?
5. Which states may emerge as future AMR hotspots based on forecasting models?

---

## Data Sources
- **CDC AR Patient Safety Portal (ARPSP)**  
  AMR resistance percentages by pathogen, year, and state  
  https://arpsp.cdc.gov/explorer

- **CDC Outpatient Antibiotic Use Data**  
  Prescriptions per 1,000 people by antibiotic class and state  
  https://arpsp.cdc.gov/profile/antibiotic-use

- **U.S. Census State Population Estimates**  
  Used for population normalization  
  https://www2.census.gov/programs-surveys/popest/

---

## Methods & Analysis
- Data cleaning and standardization across datasets
- State-level aggregation and population normalization
- Exploratory data analysis and trend analysis
- Correlation analysis between antibiotic use and resistance
- Geospatial analysis using choropleth maps
- Heatmaps for state-by-pathogen resistance patterns
- Forecasting using Tableau exponential smoothing models

---

## Visualizations
- Choropleth maps of AMR rates by state
- Time-series line charts (2019–2023)
- Scatterplots of antibiotic use vs resistance
- Heatmaps of multi-pathogen resistance
- Forecast projections through 2028–2030
- Interactive Tableau dashboards and story points

---

## Repository Contents
- **CSV files**: CDC AMR and antibiotic use datasets used for analysis  
- **Final Project PDF**: Written report and interpretation  
- **Proposal PDF**: Original project proposal  
- **Tableau `.twbx` file**: Interactive dashboards and story  
- **Demonstration video**: Walkthrough of Tableau analysis (if included)

---

## Key Findings (Summary)
- MDR *Acinetobacter* showed a sharp increase post-2020.
- Resistance trends are pathogen-specific rather than uniform.
- High-risk states show persistence rather than isolated spikes.
- Antibiotic prescribing correlates weakly to moderately with resistance, suggesting additional drivers such as hospital practices and population movement.

---

## Tools Used
- Tableau
- Microsoft Excel
- CDC ARPSP datasets
- U.S. Census data

---

## Author
**Prutha Trivedi**

---

## Notes
This repository is intended for academic and educational purposes.  
Raw data belongs to the CDC and U.S. Census Bureau.
