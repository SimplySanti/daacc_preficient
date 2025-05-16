# Preficient Data Analysis

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

This repository contains code and resources for analyzing air quality in Monterrey, using data collected from citizen sensors since 2019. The project's goal is to study the spatial and temporal dispersion of pollutants (such as PM2.5), assess data reliability, detect outliers, and build predictive models to support environmental decision-making.

## ⚙️ Installation and Usage

### 1. Clone the repository

```bash
git clone https://github.com/SimplySanti/daacc_preficient.git
cd daacc_preficient
```

### 2. Create and activate a virtual environment

```bash
python3 -m venv venv
source venv/bin/activate
```

> On Windows: `venv\Scripts\activate`

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run notebooks or scripts

```bash
jupyter notebook
```

You can also use Visual Studio Code and select the virtual environment as the Python interpreter.


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
│                         preficient_data_analysis and configuration for tools like black
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
└── preficient_data_analysis   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes preficient_data_analysis a Python module
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

## 🎯 Project Objectives

- Detect anomalous data (outliers)
- Assess the reliability of citizen sensors
- Analyze the spatial and temporal behavior of pollutants
- Explore potential pollution sources (e.g., Cadereyta refinery, traffic)
- Build interactive dashboards and predictive models

---
