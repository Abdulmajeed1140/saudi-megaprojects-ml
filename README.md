# Saudi Vision 2030 Megaprojects — Regional Economic Impact

MSc dissertation Data Analytics. Tests whether project-portfolio features predict
regional employment growth across Saudi Arabia's thirteen administrative
regions, alongside spatial concentration measures and a project-level
delay classifier.

## Files

- `saudi_megaprojects.ipynb` — full analysis, run top to bottom
- `gastat_unified_registered_employees.csv`
- `gastat_real_estate.csv`
- `gastat_population_province_sex_nationality.csv`

## Data not included

The project register is not redistributed here, as its source licence is
listed as Unknown. Download `Saudi_projects_dataset.csv` from
https://www.kaggle.com/datasets/ghadahaltwalah/saudi-projects-dataset
and place it in the same directory as the notebook.

## Running

Install dependencies from `requirements.txt`. The notebook must be run in
order, as cells are not independent.

Step 7 requires a TabPFN API token from https://ux.priorlabs.ai/ — the
notebook prompts for it at runtime and does not store it. All other steps
run without a token.
