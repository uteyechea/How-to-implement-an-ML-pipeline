# 1 How to implement an ML pipeline.
We will be working with deep learning. Following in the steps of Ian Goodfellow and his book "Deep Learning" made publicly available at http://www.deeplearningbook.org

# 2 About the development environment.

## 2.1 Setup your project structure 
<a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/"> Tutorial on how to set the folder structure for ML projects </a>, based on the cookiecutter data science project template.

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io

--------


## 2.2 Setup git account
Get familiar with commonly used git commands (GitHub)
https://gist.github.com/cferdinandi/ef665330286fd5d7127d

## 2.3 Setup virtual environment (Python)
https://docs.python.org/3/library/venv.html#creating-virtual-environments
Once the venv is setup. Learn how to build your requirements.txt file.
Using pip freeze -> requirements.txt
Video tutorial https://www.youtube.com/watch?v=N5vscPTWKOk

## 2.4 Choose your IDE
1. Visual studio code offers a nice integration with python and your venv.
2. Google Colaboratory will be useful during training if you don't have a GPU. https://colab.research.google.com/

## 2.5 Stick with a coding standard
Write code so another person can understand it.
https://www.python.org/dev/peps/pep-0008/









