# Workout Strength Analysis (R)

Exploratory data analysis and statistical modelling project in R examining how workout duration, frequency, and baseline strength impact 4 week strength progression.

# Overview
- **Data:** 443 strength training sessions and 7 400+ sets exported from Arrow workout app ('workout-data-export.json').
- **Tools:** R ('tidyverse', 'jsonlite', 'lubridate', 'ggplot2').
- **Metric:** Estimated 1-Rep Max (e1RM) calculated using Epley's formula, filtered to working sets ('reps <= 12')

# Findings
- **Diminishing Returns:** Baseline strength 4 weeks prior is a significant predictor of 4 week strength change('p = 0.0002', 'Estimate = -0.196'), which shows how strength gains plateau as lifters reach their strength ceiling.
- **Gym Durration:** Neither time in gym or total sessions ('p = 0.085', 'p - 0.98') significantly predicted progresson on Cable Lat Pulldown. This shows that total duration includes unrelated muscle groups and rest rather than volume specific to the lift in focus.

# Link to Notebook:
https://chawbolt.github.io/workout-strength-analysis/
