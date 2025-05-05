# Music Therapy Project

This repository contains a data analysis project focused on exploring the relationship between music listening habits and mental health. The project uses survey data to investigate how different music genres, listening patterns, and preferences correlate with anxiety, depression, insomnia, and other mental health indicators.

## Project Overview

This project analyzes the "Music and Mental Health Survey" dataset to understand how music affects mental wellbeing. The analysis includes:

- Examination of music listening habits across different demographics
- Correlation between music genres and mental health indicators
- Predictive modeling to identify at-risk individuals based on music preferences
- Evaluation of music's therapeutic effects on various mental health conditions

## Dataset

The main dataset used in this project is `mxmh_survey_results.csv`, which contains survey responses from participants regarding:

- Demographic information (age, etc.)
- Music listening habits (hours per day, preferred streaming services)
- Genre preferences and frequency of listening to various genres
- Self-reported mental health metrics (anxiety, depression, insomnia, OCD)
- Perceived effects of music on mental health

## Repository Structure

```
music_therapy/
├── README.md
├── experiment_runs.csv
├── Group Project final.ipynb
└── mxmh_survey_results.csv
```

## Machine Learning Models

The project explores several machine learning models to predict mental health risks based on music preferences:

- Random Forest Classifier
- Logistic Regression
- Gradient Boosting Trees (GBT)

Model performance metrics are tracked in `experiment_runs.csv`, which contains details about different model configurations and their evaluation results.

## Key Findings

The analysis reveals several interesting patterns:

- Certain genres show stronger correlations with specific mental health conditions
- Music listening duration and diversity of genres impact perceived therapeutic effects
- Active music engagement techniques show promise for improving mental health outcomes
- Different demographic groups report varying effects of music on their mental wellbeing

## Getting Started

To run this analysis:

1. Clone the repository
2. Ensure you have the required dependencies installed
3. Open the Jupyter notebook `Group Project final.ipynb`
4. Run the cells to reproduce the analysis

## Future Work

Potential extensions of this project include:

- Incorporating additional datasets on music therapy interventions
- Developing more sophisticated models with feature engineering
- Creating a recommendation system for therapeutic music based on individual profiles
- Exploring cultural and demographic differences in music therapy effectiveness

