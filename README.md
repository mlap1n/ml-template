# ml-template

## Requirements and Installation

### pip

```bash
pip install cookiecutter
```

### conda

```bash
conda config --add channels conda-forge
conda install cookiecutter
```

## To start a new project, run:

```bash
cookiecutter https://github.com/mlap1n/ml-template.git
```

## The resulting directory structure
```
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
├── notebooks          <- Jupyter notebooks.│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
├── src                <- Source code for use in this project.
    ├── __init__.py    <- Makes src a Python module
    │
    ├── data           <- Scripts to download or generate data
    │   └── make_dataset.py
    │
    ├── features       <- Scripts to turn raw data into features for modeling
    │   └── build_features.py
    │
    ├── models         <- Scripts to train models and then use trained models to make
    │   │                 predictions
    │   ├── predict.py
    |   ├── inference.py
    │   └── train.py
    │
    └── visualization  <- Scripts to create exploratory and results oriented visualizations
        └── visualize.py

```
