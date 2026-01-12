# World Cup 2026 Prediction

Notebook that builds a simple Poisson-based match model from historical World Cup data and simulates the tournament progression (group stage through knockout rounds).

## Contents
- `prediction.ipynb`: main notebook with data prep, team strength calculation, and tournament simulation.
- `Data/`: source datasets used by the notebook.

## Data inputs
The notebook reads the following files (paths are relative to the repo root):
- `Data/FIFA_World_Cup_History.csv`
- `Data/matches.csv`
- `Data/teams.csv`
- `Data/tournament_stages.csv`
- `Data/host_cities.csv`
- `Data/results.csv`

## Requirements
- Python 3
- Jupyter (or any notebook runner)
- `pandas`
- `scipy`

## Run
1. Open `prediction.ipynb` in Jupyter.
2. Run all cells top to bottom.

## Notes
- The model uses historical match data to estimate team strength, then uses a Poisson distribution to simulate scores.
- Data files are included in the repo; no network access is required.
