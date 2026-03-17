# Forest Productivity and Degradation Monitoring

Applied workflow for analysing vegetation productivity and forest degradation in the Amazon using MODIS EVI time series and Tropical Moist Forest data.

![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Google Earth Engine](https://img.shields.io/badge/Google%20Earth%20Engine-4285F4?style=flat&logo=googleearth&logoColor=white)
![Shiny](https://img.shields.io/badge/Shiny-276DC3?style=flat&logo=r&logoColor=white)

---

## Overview

This repository contains the workflows developed for a master’s project on forest productivity and degradation in Paragominas, in the Brazilian Amazon.

The analysis combines:

- MODIS EVI time series
- Tropical Moist Forest degradation information
- temporal smoothing and trend analysis
- statistical summaries and visual outputs

The goal was to compare vegetation productivity dynamics with forest degradation patterns and explore how both signals interact over time.

---

## Repository contents

| Folder | Content |
| --- | --- |
| `data_analyses/` | Main analysis scripts in R |
| `plot_scripts/` | Plotting and statistical summary scripts |
| `GEE_exportation/` | Notebooks used to access and export Earth Engine data |
| `UE801_Rapport_LucasLima.pdf` | Final project report |

---

## Workflow

The project includes:

- export and preparation of MODIS and TMF data
- temporal trend analysis of EVI signals
- comparison of productivity classes and degradation classes
- histograms, boxplots, stacked bars, and line plots
- interactive exploration through a Shiny app

---

## Main tools

- **R** for analysis, plotting, and the Shiny interface
- **Python / Earth Engine notebooks** for data access and export
- **QGIS** for map visualization and spatial checking

---

## Why this repo matters

This repository shows an early but complete remote-sensing workflow:

- Earth observation data preparation
- temporal environmental analysis
- degradation/productivity comparison
- applied research outputs in the Amazon

---

## Context

This work was developed during the SIGMA MSc in France and focused on Paragominas as a study area connected to the TerrAmaz project context.

---

## License

This project is licensed under CC BY 4.0.
