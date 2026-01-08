# Theme-Park-Ride-Injuries-Analysis

## Project Overview
This project explores reported injury incidents associated with amusement park rides between 2010 and 2017, using publicly available safety data. The analysis focuses on identifying which ride tyypes are associated with the highest number of injuries and the most common cause of injury. The goal is to provide insight into potential safety risks and patterns within amusement park environments. 

## Research Questions
  - Which amusement park ride types are associated with the highest number of reported injuries?
  - What are the most common injury causes across ride types?
  - How do injury patterns differ when accounting for ride incident frequency?

## Data Source
  - Safeparks/RidesDatabase
    Public dataset containing reported ride-related incidents, injuies, and contextual details between 2010 and 2017.

## Tools & Libraries Used
  - Python
  - Pandas
  - Matplotlib & Seaborn
  - Jupyter Notebook

## Data Cleaning & Preparation
Key preprocessing steps included:
  - Selecting relevant columns related to ride type, injury counts, causes, and venue type
  - Filling missing values for binary cause indicators (mechanical, operator error, employee) with 0
  - Handling missing injury counts using appropriate assumptions
  - Filtering the dataset to include amusement parks only
  - Creating subsets for the top 15 ride types and top 20 injury causes

## Key Findings 
  - Steel coasters were associated with the highest number of reported injuries, accounting for approximately 23% of all injuries
  - The most common injury category was body pain, representing roughly 12% of reported injuries
  - Injuries most frequently occurred during specific stages of the ride cycle, such as loading/unloading and during ride operation.

## Limitations
  - The dataset does not account for pre-existing medical conditions of injured individuals
  -Environmental factors such as weather conditions are not included
Ride exposure metrics such as number or riders, operating hours, or ride popularity were unavailable
Analysis is limited to reported incidents and may underrepresent minor injuries

## Future Work
  - Incorporating more recent data
  - Conducting location-specific analyses (e.g., comparing Florida vs. California theme parks)
  - Examining the impact of ride age, maintenance history, and renovation timelines
  - Comparing injury patterns across different park operators (Disney, Universal, SeaWorld)
