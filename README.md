# Emerging Technologies

## Overview
This repository is a project demonstrating my understanding of new technologies we have covered in the Emerging Technology module.

## About the Project
The project had a number of requirements that needed to be fulfilled in order to complete the tasks at hand.  
I was required to create two Jupyter notebooks, scikit-learn and quantum-deutsch.  
Both of these notebooks should have the ability to be ran using Docker, this enables someone to quickly run the notebooks with minimal configuration.

### scikit-learn.ipynb
This notebook should contain:
1. Overview of scikit-learn Python library.
2. Demonstrations of at least three scikit-learn algorithms.
3. Appropriate plots and other visualisations.

### quantum-deutsch.ipynb
This notebook should contain:
1. Comparison of quantum computing and classical computing.
2. Explanation of Deutsch's algorithm with code that is simulated using qiskit
There are two Jupyter notebooks in this repository:
1. Scikit-Learn - Contains overview of scikit-learn Python library and also demonstations of at least three scikit-learn algorithms.
2. Quantum-Deutsch - Contains comparison of quantum computing and classical computing, also an explanation of Deutsch's algorithm using qiskit to simulate it with code.

## Table of Contents
* [Overview](#overview)
* [About the Project](#about-the-project)
* [Technologies Used](#technologies-used)
* [How to Install](#how-to-install)
* [How to Run the Notebooks](#how-to-run-the-notebooks)
* [References](#references)

## Technologies Used
The technologies used in this project were:
1. [Python](#python)
2. [Jupyter Notebook](#jupyter-notebook)
3. [Jupyter Lab](#jupyter-lab)
4. [Docker](#docker)
5. [Scikit-Learn](#scikit-learn)
6. [NumPy](#numpy)
7. [Pandas](#pandas)
8. [MatPlotLib](#matplotlib)
9. [Seaborn](#seaborn)
10. [StatsModels](#statsmodels)
11. [Plotly](#plotly)
12. [SciPy](#scipy)

### [Python](https://www.python.org/)
Python is a general purpose and high level programming language. This means that it can be used to create a variety of different programs and isn't specialized for any specific problem.

### [Jupyter Notebook](https://jupyter.org/)
Jupyter notebooks (or “notebooks”, all lower case) are documents produced by the Jupyter Notebook App, which contain both computer code (e.g. python) and rich text elements (paragraph, equations, figures, links, etc…). Notebook documents are both human-readable documents containing the analysis description and the results (figures, tables, etc..) as well as executable documents which can be run to perform data analysis.

### [Jupyter Lab](https://jupyter.org/)
Jupyter Lab is a web-based interactive development environment for notebooks, code and data. Its flexible interface allows users to configure and arrange workflows in data science, scientific computing, computational journalism and machine learning. Jupyter Lab runs in a single tab, with sub-tabs displayed within that one tab, Jupyter Notebook opens new notebooks in new tabs. So JupyterLab feels more like an IDE.

### [Docker](https://www.docker.com/)
Docker is an open source containerization platform. It enables developers to package applications into containers—standardized executable components combining application source code with the operating system libraries and dependencies required to run that code in any environment. This will allow anyone to run my notebooks from anywhere with minimal configuration.

### [Scikit-Learn](https://scikit-learn.org/)
Scikit-learn is probably the most useful library for machine learning in Python. The sklearn library contains a lot of efficient tools for machine learning and statistical modeling including classification, regression, clustering and dimensionality reduction.

### [NumPy](https://numpy.org/)
NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

### [Pandas](https://pandas.pydata.org/)
Pandas is a widely-used data analysis and manipulation library for Python. It provides numerous functions and methods that expedite the data analysis and preprocessing steps.

### [MatPlotLib](https://matplotlib.org/)
Matplotlib is a cross-platform, data visualization and graphical plotting library for Python and its numerical extension NumPy. As such, it offers a viable open source alternative to MATLAB. Developers can also use matplotlib's APIs (Application Programming Interfaces) to embed plots in GUI applications.

### [Seaborn](https://seaborn.pydata.org/)
Seaborn is a library for making statistical graphics in Python. Seaborn helps you explore and understand your data. Its plotting functions operate on dataframes and arrays containing whole datasets and internally perform the necessary semantic mapping and statistical aggregation to produce informative plots.

### [StatsModels](https://www.statsmodels.org/)
StatsModels is a Python library built specifically for statistics. Statsmodels is built on top of NumPy, SciPy, and matplotlib, but it contains more advanced functions for statistical testing and modeling that you won't find in numerical libraries like NumPy or SciPy.

### [Plotly](https://plotly.com/)
Plotly enables Python users to create beautiful interactive web-based visualizations that can be displayed in Jupyter notebooks, saved to standalone HTML files, or served as part of pure Python-built web applications using Dash.

### [SciPy](https://scipy.org/)
SciPy in Python is an open-source library used for solving mathematical, scientific, engineering, and technical problems. It allows users to manipulate the data and visualize the data using a wide range of high-level Python commands. SciPy is built on the Python NumPy extension.

## How to Install
There are two main ways to install this project.
1. [Python](#installing-via-python)
2. [Anaconda](#installing-via-anaconda)

Both of these methods have their pros and cons.  
<br/>
[Anaconda](https://www.anaconda.com/) is an open-source package and environment management system which already comes with many of the libraries that will need to be installed manually if you choose to install this project via Python, however if you do not use Python regularly it is better practice to install via Python as it will take up much less space on your device as you will not be installing the countless libraries Anaconda provides that you will never use.

### Installing via Python
In order to install via Python you must follow these steps in order. If you already have one of the steps completed, please move on to the next step.  
Steps:
1. [Install Python](#installing-python)
2. [Install Libraries](#installing-libraries)
3. [Install Jupyter](#installing-jupyter)

#### Installing Python
For Windows:  
1. Go to [Python downloads](https://www.python.org/downloads/windows/)
2. Select [Python 3.9.0](https://www.python.org/downloads/release/python-390/) (Some libraries are not compatible with latest version)
3. Scroll to the bottom of the page and select the [64bit](https://www.python.org/ftp/python/3.9.0/python-3.9.0-amd64.exe) or [32bit](https://www.python.org/ftp/python/3.9.0/python-3.9.0.exe) installer
4. Open installer and select "Add Python 3.9 to PATH", then click "Install Now"
5. Python has been installed successfully
6. Open CMD and type `python --version`. Python 3.9.0 should be displayed  
<br/>
If Python failed on installation, you will need to go to your control panel and uninstall the existing Python package. You may then start from step 4. 
<br/><br/>

For macOS:  
1. Go to [Python downloads](https://www.python.org/downloads/macos/)
2. Select [Python 3.9.0](https://www.python.org/downloads/release/python-390/) (Some libraries are not compatible with latest version)
3. Scroll to the bottom of the page and select the [macOS](https://www.python.org/ftp/python/3.9.0/python-3.9.0-macosx10.9.pkg) installer
4. Open installer. You will be guided through the installation process.
5. Python has been installed successfully
6. Open Terminal and type `python -V`. Python 3.9.0 should be displayed  

For Other Platforms:  
1. Go to [Python downloads](https://www.python.org/download/other/)
2. Select the platform you need to install Python on and follow the tutorial

#### Installing Libraries
There are a number of libraries that are required for this project. Once Python is installed, it is a simple process to install libraries.  
Libraries:  
1. sklearn
2. numpy
3. pandas
4. matplotlib
5. seaborn
6. statsmodels
7. plotly
8. scipy  
<br/>

For Windows:  
1. Open CMD
2. For each library type 'pip install [library]'  
<br/>

For macOS:  
1. Open Terminal
2. For each library type 'pip install [library]'  
<br/>

For Other Platforms:  
1. Go to Python package installer [tutorial](https://packaging.python.org/tutorials/installing-packages/)

#### Installing Jupyter
For Windows:  
1. Open CMD
2. Type `pip install jupyterlab`  
<br/>

For macOS:  
1. Open Terminal
2. Type `pip install jupyterlab`  
<br/>

For Other Platforms:  
1. Go to [Jupyter Lab installationn](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)  
<br>

### Installing via Anaconda




## How to Run the Notebooks


### Running with Docker
1. Clone Repo
2. Open CMD and navigate to cloned repo
3. Run `docker-compose up`
4. Once deployed, copy the provided link and paste it as a URL

# References
