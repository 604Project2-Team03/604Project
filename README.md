# 604Project

## Introduction

This notebook serves as an introduction to using **Apache Beam**, an industrial standard for data processing. It covers fundamental concepts such as Map, FlatMap, and ParDo, along with a detailed example of a data processing pipeline that utilizes aggregated functions.

## How to Use

To start going through this notebook, you would need to get **Apache-Beam** running on Python.

I would suggest doing it in the following 3 ways:

1. **Conda**

if you have **conda** installed in you operating system, you can run:
```
conda create -n "604Project" python=3.12
conda activate 604Project
pip install -r requirements.txt
jupyter lab
```

2. **Venv**

if you have generic **Python** installed, you can run:
```
python -m venv 604Project

604Project\Scripts\activate #Windows
source 604Project\Scripts\activate #Mac/Unix

pip install -r requirements.txt
jupyter lab
```

3. **Online Playground**

if you don't wanna do either, you can just go to [Apache Beam Playground](https://play.beam.apache.org/?path=SDK_PYTHON_FlatMap&sdk=python). You can just copy your code into the cells and run it.