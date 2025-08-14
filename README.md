# Geospatial Comparative Analysis: Iran vs Italy

![Sample Visualization](sample_image.png)

This repository contains a comprehensive geospatial analysis comparing land use/land cover (LULC) and nighttime lights between Iran and Italy using Google Earth Engine and Python.

## Project Overview

This project performs comparative geospatial analysis between Iran and Italy, focusing on:
- Nighttime light intensity analysis (2015-2023)
- Land Use/Land Cover (LULC) classification (2021)
- Accuracy assessment of ESA WorldCover data
- Statistical comparison of land cover distributions

## Features

- **Nighttime Lights Analysis**:
  - VIIRS monthly composite data processing
  - Multi-year average computation
  - Logarithmic scaling for visualization
  - Comparative visualization between countries

- **Land Use/Land Cover Analysis**:
  - ESA WorldCover data processing (10m resolution)
  - Area statistics calculation for all land cover classes
  - Interactive visualization with custom legends
  - Comparative bar charts of land cover distribution

- **Accuracy Assessment**:
  - Reference point collection
  - Confusion matrix generation
  - Precision, recall, and F1-score calculations
  - Visualization of accuracy metrics

## Technologies Used

- Google Earth Engine Python API
- Geemap for interactive mapping
- Matplotlib and Seaborn for visualization
- Pandas for data analysis
- Jupyter Notebook for interactive development

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Geospatial-Comparative-Analysis.git
