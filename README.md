# Smarter Outreach — Finding Who to Reach and Who Not To

## Overview

This repository contains a home assignment project for WellCo, focused on identifying the optimal outreach strategy to reduce churn rates.

The project trains predictive models to estimate the effect of outreach and ranks members based on their potential to benefit from being contacted.

## Results

The main results are located in `notebooks/results/`.

The folder includes a CSV file (`all_outreach_candidates.csv`) containing:

- Each member's rank and score, indicating outreach priority.

Evidence suggests that members with scores in the lowest quartile (below 25%) should not be reached out to, as outreach may increase churn.

## How to Run

To reproduce the results locally:

### Install requirements

```bash
pip install -r requirements.txt
```

(Make sure to do this inside your virtual environment.)

### Run the following notebooks in order:

1. `notebooks/02_data_creation.ipynb`
2. `notebooks/03_ranking_modeling.ipynb`

After execution, the file `notebooks/results/all_outreach_candidates.csv` will be updated with new rankings and scores based on your input data (must have the same schema as the original dataset).

## Executive Summary

A short presentation summarizing the approach and findings is available at:
`slides/Smarter Outreach_ Finding Who to Reach— and Who Not To.pdf`

