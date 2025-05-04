# Snow Crab Data Exploration

This repository contains a Jupyter Notebook analyzing snow crab catch data, with a focus on CPUE (Catch Per Unit Effort) trends across time and space.

The main goal of the notebook is to generate an animated map showing average CPUE varying location and over the years.

## Files

- `exploration.ipynb`: Main notebook containing data loading, processing, and visualization.
- `mfsnowcrab.csv`: Raw snow crab survey data.

## Getting Started

1. Clone the repository.
2. Open `exploration.ipynb` in Jupyter.
3. Make sure `mfsnowcrab.csv` is in the same directory as the notebook.

### Requirements

This project uses the following Python libraries:

- pandas
- geopandas
- numpy
- matplotlib
- plotly
- shapely
- pyproj
  
```bash
pip install pandas geopandas matplotlib plotly numpy shapely
