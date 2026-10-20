# Traffic Data Analysis

A Python exploratory data analysis project for examining vehicle-count patterns over time and across road junctions.

## Dataset
This project is designed for the public [Traffic Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/fedesoriano/traffic-prediction-dataset).

**The dataset CSV is not included in this repository.** Download it from Kaggle and place the CSV in this folder before running the notebook.

The notebook expects columns similar to `DateTime`, `Junction`, and `Vehicles`. It attempts to detect common variants and prints the columns it finds.

## Questions explored
- How are vehicle counts distributed?
- Which hours have the highest and lowest average counts?
- How do average counts vary by day of the week?
- How do counts compare across junctions, when a location column is available?
- How do average counts change over time?

## Tools
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Run the project
1. Download the CSV dataset from Kaggle.
2. Put the CSV in this folder alongside `traffic_data_analysis.ipynb`.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the notebook:
   ```bash
   jupyter notebook traffic_data_analysis.ipynb
   ```
5. Run all cells from top to bottom and review the generated tables, charts, and observations.

## Important note
Results are generated from the dataset when the notebook is run. Do not add numerical findings to this README until you have run the notebook and checked the outputs. This repository is a recreated version of a traffic-analysis project, not a recovered copy of files from a previous computer.
