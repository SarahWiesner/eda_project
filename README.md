# EDA project
This is a notebook on my first EDA project.


Topic: Real estate agent's recommendations for a customer (buyer), based on data about house units sold in one year.

## Contents

This repository contains the Jupyter notebook [EDA](./eda.ipynb) as its main item. In this notebook, all the data work, including cleaning, analysis and visualization is collected. 

Furthermore, you can find the [presentation](./EDA_project_slides.pdf) given within the neuefische DS bootcamp.


## Requirements and Setup

- pyenv
- python==3.9.8


This repo contains a [requirements.txt](./requirements.txt) file with a list of all the packages and dependencies you will need. Before you install the virtual environment, make sure to install postgresql if you haven't done it before.

```bash
brew update
brew install postgresql
```

In order to install the environment you can use the following commands:

```
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```