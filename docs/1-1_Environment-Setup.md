# Index

#### Part I: Data analysis
- [1.0 | Intro into the dataset](1-0_Intro-Dataset.md)
- [1.1 | Setup your data analysis environment](1-1_Environment-Setup.md)
- [1.2 | Further readings on data analysis](1-2_Collection-Data-Analysis-Libraries.md)

#### Part II: Animated data stories
- [2.0 | About data stories](2-0_Intro-Datastories.md)
- [2.1 | Further readings on animated data stories](2-1_Collection-Animated-Datastories.md)

---
# 1.1 Setup your data analysis environment
The following readme walks you through the suggested environment setup on your PC, for the data analysis part. 
We will use `python3` and `jupyter notebooks` for our examples. Feel free to use any software/language, that matches your skills and requirements.

To execute the example notebooks the following software needs to be installed in advance. If you have parts already installed simply jump over to the next point.

## Python
Download and install Python (We recommend python 3.9+). Simply follow the official installation instructions.

`https://www.python.org/downloads/`

If you have multiple python version installed [PyEnv](https://github.com/pyenv/pyenv) may be helpful.

## virtualenv

You may want to use a virtual environment for this project.
A good intro, why and how you should use it can be found in this article: https://realpython.com/python-virtual-environments-a-primer/

Create a new `virtualenv`

```shell
python3 -m venv YOUPATH/hackatum2021/venv
```

Activate the new environment:
```shell
source YOUPATH/hackatum2021/venv/bin/activate
```

## Python Modules
Install at least the following python modules in your virtual environment:
```shell
pip install jupyter lab
```
```shell
pip install pandas
```
```shell
pip install matplotlib
```
```shell
pip install kats
```
```shell
pip pip install scikit-learn
```

## Let's go!
Start Jupyter lab, open the URL shown in your terminal and explore the examples in `notebooks/`
```shell
jupyter lab
```

[Next: 1.2 | Further Readings on data analysis](1-2_Collection-Data-Analysis-Libraries.md)