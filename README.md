# Republic Database of Private Entities

This repo contains scripts for calculating some statistics from the Republic Database of Private Entities (rus. Государственная база данных физических лиц).

Specifically:

- `life_table.ipynb` — Life tables, death rates and probabilities, life expectancy, population by age for a certain year;
- `death_rates.ipynb` — Death rates for specific months in a year;
- `infant_mortality.ipynb` — Infant mortality rates (stillbirth, neonatal, perinatal deaths, etc.).

Statistics are calculated on synthetic data, which are created in `synthetic_data.ipynb` and preprocessed in `preprocess.ipynb`. The data are extracted from `data/raw` and final statistics are saved into `result`.