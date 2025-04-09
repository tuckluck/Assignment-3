# Assignment-3

[![python](https://img.shields.io/badge/python-3.12-blue.svg)](https://www.python.org/)
![os](https://img.shields.io/badge/os-ubuntu%20|%20macos%20|%20windows-blue.svg)
[![license](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/sandialabs/sibl#license)


[![codecov](https://codecov.io/gh/tuckluck/Assignment2/graph/badge.svg?token=TKF4CLV1G5)](https://codecov.io/gh/tuckluck/Assignment2)
[![tests](https://github.com/tuckluck/Assignment2/actions/workflows/testsDS.yml/badge.svg)](https://github.com/tuckluck/Assignment2/actions)


Welcome to the Assignment 3 repo. Please follow the directions below to download and run the code 

To install this package, please begin by setting up a conda environment (mamba also works):
```bash
conda create --name tl_Assignment3-env python=3.12
```
Once the environment has been created, activate it:

```bash
conda activate tl_Assignment3-env
```
Double check that python is version 3.12 in the environment:
```bash
python --version
```
Ensure that pip is using the most up to date version of setuptools:
```bash
pip install --upgrade pip setuptools wheel
```

Create an editable install of the code (note: you must be in the correct directory):
```bash
pip install -e .
```


Setup juypter notebook for tutorials

```bash
pip install jupyter
```

Run Tutorial
```bash
jupyter notebook Part4_tutorial_A-C.ipynb
```


