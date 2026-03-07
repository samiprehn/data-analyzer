# 📊 Data Analyzer

A single-page CSV data explorer and automated EDA (Exploratory Data Analysis) tool. Drop in any CSV and instantly get a full statistical profile — no setup, no backend, no dependencies.

## Features

- **Column profiling** — data types, missing values, unique counts, min/max/mean/median
- **Hypothesis testing** — automatic statistical tests based on data types
- **Correlation heatmap** — visualize relationships between numeric columns
- **Pair plot** — scatter matrix for multivariate exploration
- **ML task suggestion** — recommends classification, regression, or clustering based on your data
- **Feature importance** — ranks columns by predictive relevance
- **Encoding & scaling recommendations** — tells you how to prepare each column for ML

## Usage

1. Open the app
2. Drag and drop a CSV file (or click to browse)
3. Explore the auto-generated analysis

No data leaves your browser — everything runs client-side.

## Running Locally

```bash
open index.html
```

Or serve with any static file server:

```bash
npx serve .
```

## Tech

Pure HTML, CSS, and vanilla JavaScript. Zero dependencies.
