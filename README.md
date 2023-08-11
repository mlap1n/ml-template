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
├── configs
├── data
├── docs                     <- A default Sphinx project; see sphinx-doc.org for details
├── LICENSE
├── notebooks                <- Jupyter notebooks.
|
├── README.md                <- The top-level README for developers using this project.
|
├── reports                  <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures              <- Generated graphics and figures to be used in reporting
|
├── requirements.txt         <- The requirements file for reproducing the analysis environment, e.g.
│                             generated with `pip freeze > requirements.txt`
├── scripts
├── setup.cfg                <- makes project pip installable (pip install -e .) so src can be imported
├── setup.py
├── src                      <- Source code for use in this project.
│   ├── __init.py__          <- Makes src a Python module
│   ├── models               <- Scripts to train models and then use trained models to make
    │   │                     predictions
│   │   └── __init__.py
│   ├── utils
│   │   └── __init__.py
│   └── visualization        <- Scripts to create exploratory and results oriented visualizations
│       └── __init__.py
└── tests

```
