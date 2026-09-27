## F1 Race Forecasts
A machine learning project that forecasts Formula 1 race results using historical and event specific data.
Forecasts are generated for each Grand Prix once the required event data is available, including qualifying results and the confirmed starting grid.
## Method
The models were developed using historical Formula 1 data, with 2014–2022 dataset used for training, 2023 for validation, and 2024–2025 as the final test set.
The forecasting pipeline is frozen before prospective predictions are published. Each release records the model version, prediction time, inputs and results so forecasts can be evaluated without modifying them after a race.

## Data Sources
Historical and event data are obtained from Jolpica/Ergast and publicly available Formula 1 and FIA sources.
