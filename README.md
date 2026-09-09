# FIFA World Cup 2026 Data Science Project

## Project overview

This repository contains the Python analysis completed for HIT140 Foundations of Data Science Assessment 2. The project uses FIFA World Cup 2026 datasets to complete four distinct analytical tasks.

Each task includes:

* An analytical question
* Data cleaning and wrangling
* Data preparation and sampling
* Descriptive statistics
* A 95% confidence interval
* A one-sample or two-sample t-test
* Data visualisation
* Interpretation of results and limitations

## Analytical tasks

### Task 1: Attacking threat analysis

Notebook: `attacking_threat_amit.ipynb`

This task examines attacking performance using the supplied squad-level standard and shooting datasets.

Required files:

* `squad_standard.csv`
* `squad_shooting.csv`
* `task1_sample.csv`
* `task1_boxplot.png`

### Task 2: Shooting accuracy analysis

Notebook: `Shooting_Accuracy_Roshan.ipynb`

This task analyses player shooting accuracy using the supplied player-level standard and shooting datasets.

Required files:

* `player_standard.csv`
* `player_shooting.csv`
* `task2_sample.csv`
* `task2_boxplot.png`

### Task 3: Fouls committed per 90 minutes

Notebook: `FIFA2026_Task3_Fouls_Per90.ipynb`

Analytical question:

**Is the average number of fouls committed per 90 minutes different between midfielders and defenders who played at least 180 minutes?**

This task merges player standard and miscellaneous statistics, calculates fouls per 90 minutes and uses stratified random sampling to select 120 midfielders and 120 defenders.

The analysis includes descriptive statistics, 95% confidence intervals, a Welch two-sample t-test, assumption checks and a Mann–Whitney U sensitivity test.

Main result:

Midfielders averaged approximately 1.198 fouls per 90 minutes, compared with 0.899 for defenders. The estimated mean difference was 0.299 fouls per 90 minutes. Welch’s two-sample t-test found a statistically significant difference, with p = 0.002.

Required files:

* `player_standard.csv`
* `player_miscellaneous.csv`
* `task3_sample.csv`
* `task3_boxplot.png`
* `README_Task3_Nabin.txt`

### Task 4

Task 4 files and analysis will be added by the responsible group member.

## Software requirements

The analyses require Python 3 and the following packages:

* pandas
* NumPy
* SciPy
* Matplotlib
* Jupyter Notebook

Install the required packages with:

```bash
pip install pandas numpy scipy matplotlib notebook
```

## Running the analyses

1. Clone or download this repository.
2. Keep the notebooks and required CSV datasets in the same folder.
3. Open the relevant `.ipynb` file in Jupyter Notebook.
4. Run all cells from top to bottom.
5. Review the generated statistics, confidence intervals, hypothesis-test results and visualisations.

## Collaboration

The project is managed through GitHub using individual commits, branches and pull requests. Each team member is responsible for documenting and submitting evidence of their contribution through the group’s designated Microsoft Teams space.

