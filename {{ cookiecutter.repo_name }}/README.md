{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Usage
-----

- Install requirements using pip in a virtual environment (e.g. venv)
- `make help`

Project Organization
---------------------

```txt
    ├── LICENSE
    ├── Makefile    <- Makefile with commands like `make data` or `make train`
    ├── README.md   <- The top-level README for developers using this project.
    ├── data
    │   ├── external    <- Data from third party sources.
    │   ├── interim     <- Intermediate data that has been transformed.
    │   ├── processed   <- The final, canonical data sets for modeling.
    │   └── raw         <- The original, immutable data dump.
    │
    ├── docs         <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models       <- Trained and serialized models,
    │                   model predictions, or model summaries
    │
    ├── notebooks    <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                   the creator's initials, and a short `-` delimited description
    │                   , e.g. `1.0-jqp-initial-data-exploration`.
    │
    ├── references   <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports      <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures   <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing
    │                         the analysis environment, e.g. generated with
    │                         `pip freeze > requirements.txt`
    │
    ├── scripts    <- used to keep short python scripts
    │
    ├── setup.py   <- makes project pip installable
    │                 (pip install -e .) so src can be imported
    │
    ├── src   <- Source code for use in this project.
    │   ├── __init__.py   <- Makes src a Python module
    │   │
    │   ├── data   <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features   <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models   <- Scripts to train models
    │   │   │           and use them to make predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization   <- Scripts to create exploratory
    │       │                  and results oriented visualizations
    │       └── visualize.py
    │
    ├── tests   <- pytest tests
    │
    ├── test_environment.py   <- Environment testing code
    │
    └── tox.ini   <- tox file with settings for running tox; see tox.testrun.org
```

Project based on the <https://drivendata.github.io/cookiecutter-data-science/>
cookiecutter data science project template. #cookiecutterdatascience
