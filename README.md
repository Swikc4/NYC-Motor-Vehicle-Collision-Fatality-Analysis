# NYC Motor Vehicle Collision Fatality Analysis

Academic team analysis completed for CIS 3920 Data Mining for Business Analytics at Baruch College in Spring 2026.

## Overview

This analysis examined whether Ford vehicle involvement was independently associated with fatal crash outcomes after accounting for driver, vehicle, and time related factors in NYC motor vehicle collision data.

I worked as part of a four person team with Shazrim Farin, Ethan Ma, and Geovanni Ramos.

## Materials

* [`team_project_details.md`](team_project_details.md) documents the final research question, dataset, model, findings, and team attribution.
* [`results/model_output.txt`](results/model_output.txt) contains the statsmodels binary logistic regression output from the analysis.

## Dataset

The dataset in `data/Motor_Vehicle_Collisions_-_Crashes.csv` was provided by the professor.

The analysis started with 89,102 collision records across 27 columns. After cleaning and preparing the modeling data, the final dataset contained 70,272 observations.

Fatal crashes were very rare in the final dataset, with 39 fatal crashes, or about 0.055 percent of observations.

## Methods

Python, pandas, binary logistic regression, data cleaning, feature engineering, model evaluation, and statistical interpretation.

## Key Findings

Ford involvement was not statistically significant at the 0.05 level after controlling for the other variables in the model.

Large vehicle involvement was positively associated with fatal crash risk, while rush hour crashes were negatively associated with fatal outcomes in the fitted model.

## Team Context

The course was conceptual, and the Python code was provided by the professor. This repository contains the project write-ups and model output, not the original Python code.

This was completed by a four person academic team. The repository documents the analysis without presenting the full team work as my individual contribution.

## How to Explore

This repository documents the analysis and its results. Start with `team_project_details.md` for the research question, dataset, and findings, then see `results/model_output.txt` for the full statsmodels binary logistic regression output, including descriptive statistics and model coefficients. The analysis used Python, pandas, and statsmodels.
