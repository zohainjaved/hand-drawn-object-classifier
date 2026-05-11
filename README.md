# Living vs Non-Living Hand-Drawn Object Classification

A computer vision and statistical analysis project exploring whether simple geometric features can classify hand-drawn objects as living or non-living.

## Overview

This project uses 112 hand-drawn 45x45 pixel sketches across 8 categories:

### Living
- Cherry
- Banana
- Lemon
- Tree

### Non-Living
- Envelope
- Golf Club
- Pencil
- Wine Glass

The project extracts geometric and topological features from the drawings and performs statistical analysis and machine learning classification.

## Features Extracted

- Pixel count (`nr_pix`)
- Height
- Width
- Aspect ratio
- Connected regions
- Hollowness
- Roughness (custom feature)

## Methods Used

- Feature engineering
- Histogram analysis
- T-tests
- Correlation analysis
- Linear regression
- Logistic regression

## Key Findings

- `nr_pix` was the strongest classifier between living and non-living objects.
- `width` was also highly significant.
- `aspect_ratio` showed little statistical usefulness.

## Tools

- Python
- NumPy
- Pandas
- SciPy
- Matplotlib
- scikit-learn

## Files

- `report.pdf` — full assignment report
- `analysis_[k].ipynb` — feature extraction and analysis notebook
- `images/` — dataset of hand-drawn sketches
- `features.csv` — extracted feature dataset
