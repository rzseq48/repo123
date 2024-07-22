# Stack Overflow Developer Survey Analysis

## Overview

This project applies PySpark for data processing and analysis of the Stack Overflow Developer Survey 2023 dataset. The project is divided into a series of parts to explore various insights from the dataset.

## Dataset

The dataset used is from the Stack Overflow Developer Survey 2023, which can be downloaded from [Stack Overflow Developer Survey](https://survey.stackoverflow.co/). The dataset is available as a zip file containing:
- `survey_results_public.csv` (CSV file with survey data)
- `survey_results_schema.csv` (Schema CSV file)
- `survey_results.pdf` (PDF of the original survey form)

The dataset includes over 89,000 rows and 84 columns.

## Project Structure

- **Stack_Overflow_Survey_Analysis.ipynb**: Jupyter Notebook containing the analysis and visualizations.

## Analysis

The project focuses on the following questions:
1. **Which programming languages are the most desired by developers?**
   - Counts the occurrences of each programming language in the 'LanguageWantToWorkWith' column.

2. **What is the distribution of interest in programming languages by region?**
   - Groups the data by 'Country' and 'Language', counts occurrences, and visualizes the distribution using a heatmap.

## Dependencies

- [PySpark](https://spark.apache.org/docs/latest/api/python/)
- [Seaborn](https://seaborn.pydata.org/)
- [Matplotlib](https://matplotlib.org/)

## Installation

Ensure you have the following dependencies installed:

```bash
pip install pyspark seaborn matplotlib
Usage: 
git clone https://github.com/rzseq48/repo123.git
