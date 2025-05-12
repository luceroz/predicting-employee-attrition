# Predicting Employee Attrition

This project builds a machine learning pipeline to predict which employees are at risk of leaving a company, using HR data. The goal is to empower Human Resources departments to proactively intervene and reduce attrition-related costs.

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

cookiecutter

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         predicting_employee_attrition and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── predicting_employee_attrition   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes predicting_employee_attrition a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------

## How To Reproduce

1. Clone the repository
   ```bash
   git clone https://github.com/luceroz/predicting-employee-attrition.git
   cd predicting-employee-attrition
3. Set up the environment
   ```bash
   pip install -r requirements.txt
5. Run notebooks in order under /notebooks/
   - 01_EDA.ipynb
   - 02_Cleaning.ipynb
   - 03_Feature_Engineering.ipynb
   - 04_Modeling.ipynb
   - 05_Model_Tuning.ipynb
   - 06_Interpretation.ipynb
7. Generate Report
   - Final figures are stored in /reports/figures


## Project Links
- [Final Report (PDF)](https://drive.google.com/file/d/11BTDEYlNZFiPs5S_eaE_PQKM9nFKcfc3/view?usp=drive_link)
- [Slide Deck (Google Slides)](https://docs.google.com/presentation/d/1tQBR0kJ2RE90CZ24rCsgjDdydAXyqQMD2nIJhCLCNBM/edit?usp=drive_link)
- [Presentation Video](https://drive.google.com/file/d/1-V5uPAzntKHNoq8Uj--mQlXt0Fx0XF2G/view?usp=drive_link)
