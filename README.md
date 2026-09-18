## Flight Price Prediction

This project explores flight ticket prices through data cleaning, validation, and visual analysis. It is designed to identify patterns that influence airfare and support better understanding of flight pricing.

## Project Files

- `Project.ipynb` — Cleans and validates the flight-price dataset.
- `visual.ipynb` — Creates visualisations and explores relationships in the data.

## Objectives

- Prepare the dataset for analysis by handling data-quality issues.
- Validate the cleaned data and its key fields.
- Analyse how factors such as airline, route, stops, travel date, and duration relate to ticket prices.
- Communicate findings through clear visualisations.

## Workflow

1. Load and inspect the raw dataset.
2. Clean and validate the data in `Project.ipynb`.
3. Explore trends and relationships in `visual.ipynb`.
4. Interpret the visual results to understand flight-price patterns.

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## How to Run

1. Clone or download this repository.
2. Initialise the project and virtual environment:
	```bash
	uv init
	uv venv
	.venv\Scripts\activate
	uv add -r requirements.txt
	```
3. Open the notebooks in Jupyter Notebook or JupyterLab.
4. Run `Project.ipynb` first, followed by `visual.ipynb`.

## Key Outcome

The project provides a structured, visual exploration of the factors associated with flight prices and demonstrates a complete data-analysis workflow from data preparation to insight generation.
