# Movie Analysis

This repository contains an SC1015 mini-project focused on analyzing the factors that influence movie revenue. The project uses a Kaggle movie dataset and follows a notebook-based workflow covering data cleaning, exploratory analysis, and regression-driven modelling.

## What This Project Shows

- practical data analysis using Python notebooks
- structured cleaning and feature preparation before modelling
- exploratory work on movie metadata such as budget, popularity, runtime, release timing, and ratings
- applied regression experiments for understanding revenue-related patterns

## Tools Used

- Python
- pandas
- NumPy
- seaborn
- matplotlib
- scikit-learn
- Jupyter Notebook

## Repository Layout

The main project files are inside the nested `Movie-Analysis/` folder:

- `Movie-Analysis/movie1.csv`: raw dataset
- `Movie-Analysis/data cleaning.ipynb`: cleaning and preprocessing notebook
- `Movie-Analysis/clean_data.csv`: cleaned dataset exported from preprocessing
- `Movie-Analysis/MAIN.ipynb`: exploratory analysis and modelling notebook
- `Movie-Analysis/README.md`: original short team README

## Workflow

1. Start with the raw data in `movie1.csv`.
2. Use `data cleaning.ipynb` to remove unused columns, filter problematic rows, split release dates, and prepare the final analysis dataset.
3. Use `clean_data.csv` in `MAIN.ipynb` to perform exploratory analysis and compare regression-based approaches for revenue prediction.

## Project Focus

The notebooks explore questions such as:

- which variables appear most related to movie revenue
- how budget and popularity relate to revenue outcomes
- how runtime, release month, release year, and vote average affect results
- how different regression approaches compare on the cleaned dataset

## Contributors

- `@weiyanwy`
- `@EZQQQQ`
- `@Unknown0u0`
