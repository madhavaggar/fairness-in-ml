# Fairness in Machine Learning

This project demonstrates how make fair machine learning models. We would like to give credits to: https://github.com/equialgo/fairness-in-ml/, whose code we have borrowed and modified for the purposes of this assignment.

## Notebooks

- `fairness-in-torch.ipynb`: Main file where you have to implement stuff.
- `playground/*`: Various experiments.

## Getting started

This repo uses conda's virtual environment for **Python 3**.

Install (mini)conda if not yet installed.

For MacOS:

```sh
$ wget http://repo.continuum.io/miniconda/Miniconda-latest-MacOSX-x86_64.sh -O miniconda.sh
$ chmod +x miniconda.sh
$ ./miniconda.sh -b
```

`cd` into this directory and create the conda virtual environment for Python 3 from `environment.yml`:

```sh
$ conda env create -f environment.yml
```

Activate the virtual environment:

```sh
$ source activate fairness-in-ml
```

Install the `fairness` library:

```sh
$ python setup.py develop
```
