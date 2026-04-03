# Project 3 - Data Visualization

**Course:** CIVE 202 - Civil Engineering Analysis II | Spring 2026  
**Project Designer:** Arturo Garcia  
**Client:** Federal Highway Administration (FHWA)

## Project Summary

Transportation systems are among the most critical components of the economy and daily life. To support informed decision-making, this project explores and visualizes two highly influential datasets provided by the United States Department of Transportation:
1. **National Household Travel Survey (NHTS):** Provides insights into transportation usage characteristics, household vehicle types, and travel patterns across the U.S.
2. **Next Generation Simulation (NGSIM):** Focuses on microscopic driving behavior and vehicle trajectories to support the development of behavioral algorithms in traffic simulation.

As part of the Federal Highway Administration (FHWA) project, this repository contains the Python scripts and data necessary to clean, organize, and generate visualizations (such as count plots, overlaid histograms, boxplots, violin plots, and time-series line graphs mapping an Intelligent Driver Model) to assist the transportation planning group.

## Repository Contents

This repository contains the following files:

* **`Garcia_Project3_CIVE202_Spring26.ipynb`**: The main Jupyter Notebook containing all the Python code, sequential prompts, data exploration, and visualizations for both the NHTS and NGSIM datasets.
* **`NHTS.csv`**: The National Household Travel Survey dataset containing categorical and numerical data regarding household travel habits.
* **`NGSIM.csv`**: The Next Generation Simulation dataset containing time-series traffic simulation data (speeds, positions, accelerations).
* **`Garcia_ACD_Project3_CIVE202_SP26.pdf`**: A breakdown of the code structure, libraries, and logic used in the Jupyter Notebook to automate the visualizations.
* **`Garcia_Report_Project3_CIVE202_SP26.pdf`**: The final engineering report containing the background, methodology, results, and discussion of the visualizations' relevance to the transportation industry.
* **`Timesheet.xlsx`**: Project timesheet tracking tasks and distribution of work.

## Requirements and Setup

To run the Jupyter Notebook, ensure you have Python installed along with the following libraries:
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`

You can install the required dependencies using pip:
```bash
pip install pandas numpy matplotlib seaborn
