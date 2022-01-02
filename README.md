# Emerging Technologies
<b>Name:</b> Patrick Murray  
<br>
<b>Student ID:</b> G00344530
***

## Overview
This repository is a project demonstrating my understanding of new technologies we have covered in the Emerging Technology module.

## Table of Contents
* [Overview](#overview)
* [About the Project](#about-the-project)
* [Repository Contents](#so-what-is-in-this-repository)
* [Technologies Used](#technologies-used)
* [How to Install](#how-to-install)
* [How to Run](#how-to-run)
* [References](#references)

## About the Project
This project had a number of requirements that needed to be fulfilled in order to complete the tasks at hand.  
I was required to create two Jupyter notebooks, `scikit-learn.ipynb` and `quantum-deutsch.ipynb`.
Both of these notebooks should have the ability to be ran using Docker, this enables someone to quickly run the notebooks with minimal configuration.

### `scikit-learn.ipynb`
This notebook should contain:
1. Overview of scikit-learn Python library.
2. Demonstrations of at least three scikit-learn algorithms.
3. Appropriate plots and other visualisations.

### `quantum-deutsch.ipynb`
This notebook should contain:
1. Comparison of quantum computing and classical computing.
2. Explanation of Deutsch's algorithm with code that is simulated using qiskit

## So what is in this Repository
* scikit-learn.ipynb - Contains a clear concise overview of the [scikit-learn](https://scikit-learn.org/stable/) library. In this notebook I demonstrate two categories of machine learning algorithms which are supervised and unsupervised. Instead of using three algorithms, I chose to use three tasks which I demonstrated using numerous algorithms which I will explain below.

  * Classification (Supervised)
    * [Logistic Regression](https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression)
    * [K-Nearest Neighbours Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
  * Regression (Supervised)
    * [Linear Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)
  * Clustering (Unsupervised)
    * [Hierarchical Clustering](https://scikit-learn.org/stable/modules/clustering.html#hierarchical-clustering)
    * [K-Means](https://scikit-learn.org/stable/modules/clustering.html#k-means)  

  I use a different dataset for each task which were Wine Quality (Classification), Vehicle (Regression) and Country Data (Clustering). I have also used three different   plotting libraries which were pyplot, seaborn and plotly to make my notebook more visually pleasing by having a wider  range of visualization tools.

* quantum-deutsch.ipynb - Contains a clear concise comparison of quantum computing and classical computing. This notebook also explains [Deutsch's algorithm](https://en.wikipedia.org/wiki/Deutsch%E2%80%93Jozsa_algorithm) along with the preliminaries used.  Deutsch's algorithm is then simulated using [qiskit](https://qiskit.org/).

* Datasets - Contains the datasets used in `scikit-learn.ipynb` in `.csv` format.

* Dockerfile - Script file for docker which contains various commands and arguments that allows an instance of jupyter lab to be created using the dependencies in requirements.txt.

* requirements.txt - Describes all required dependencies that are used to create a docker image.

* Labs - Contains all the notebooks I have used this semester.

## Technologies Used
The technologies used in this project were:
1. [Python](#python)
2. [Jupyter Notebook](#jupyter-notebook)
3. [Jupyter Lab](#jupyter-lab)
4. [NbViewer](#nbviewer)
5. [Binder](#binder)
6. [Docker](#docker)
7. [Scikit-Learn](#scikit-learn)
8. [NumPy](#numpy)
9. [Pandas](#pandas)
10. [MatPlotLib](#matplotlib)
11. [Seaborn](#seaborn)
12. [StatsModels](#statsmodels)
13. [Plotly](#plotly)
14. [SciPy](#scipy)
15. [Qiskit](#qiskit)

### [Python](https://www.python.org/)
Python is a general purpose and high level programming language. This means that it can be used to create a variety of different programs and isn't specialized for any specific problem. Notebooks use Python so it was essential to use Python for this project.

### [Jupyter Notebook](https://jupyter.org/)
Jupyter notebooks (or “notebooks”, all lower case) are documents produced by the Jupyter Notebook App, which contain both computer code (e.g. python) and rich text elements (paragraph, equations, figures, links, etc). Notebook documents are both human-readable documents containing the analysis description and the results (figures, tables, etc) as well as executable documents which can be run to perform data analysis.

### [Jupyter Lab](https://jupyter.org/)
Jupyter Lab is a web-based interactive development environment for notebooks, code and data. Its flexible interface allows users to configure and arrange workflows in data science, scientific computing, computational journalism and machine learning. Jupyter Lab runs in a single tab, with sub-tabs displayed within that one tab, Jupyter Lab opens new notebooks in new tabs. This helps to visualize the two notebooks in this project and allows for simple modification to both notebooks.

### [NbViewer](https://nbviewer.org/)
NbViewer is a web application that lets you enter the URL of a Jupyter Notebook file, renders that notebook as a static HTML web page, and gives you a stable link to that page which you can share with others. This is used in the how to run section below to help visualise the notebooks statically without any configuration.

### [Binder](https://mybinder.org/)
Binder is an online service for building and sharing reproducible and interactive computational environments from online repositories. This is also used in the how to run section below to help launch the notebooks dynamically to allow for easy interactions.

### [Docker](https://www.docker.com/)
Docker is an open source containerization platform. It enables developers to package applications into containers—standardized executable components combining application source code with the operating system libraries and dependencies required to run that code in any environment. This will allow anyone to run my notebooks from anywhere with minimal configuration by building everything on a server without the need to download all the software on your personal machine.

### [Scikit-Learn](https://scikit-learn.org/)
Scikit-learn is probably the most useful library for machine learning in Python. The sklearn library contains a lot of efficient tools for machine learning and statistical modeling including classification, regression, clustering and dimensionality reduction. This library is  demonstrated in `scikit-learn.ipynb`, where I build numerous machine learning models.

### [NumPy](https://numpy.org/)
NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays. This helps me to perform more efficient calculations by providing me with faster and more compact arrays.

### [Pandas](https://pandas.pydata.org/)
Pandas is a widely-used data analysis and manipulation library for Python. It provides numerous functions and methods that expedite the data analysis and preprocessing steps.

### [MatPlotLib](https://matplotlib.org/)
Matplotlib is a cross-platform, data visualization and graphical plotting library for Python and its numerical extension NumPy. As such, it offers a viable open source alternative to MATLAB. I mainly use [Pyplot](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.html#:~:text=pyplot%20is%20a%20state%2Dbased,pyplot%20as%20plt%20x%20%3D%20np) which allows me to visualize the data by plotting points and creating graphs.

### [Seaborn](https://seaborn.pydata.org/)
Seaborn is a library for making statistical graphics in Python. Seaborn helps you explore and understand your data. Its plotting functions operate on dataframes and arrays containing whole datasets and internally perform the necessary semantic mapping and statistical aggregation to produce informative plots.

### [StatsModels](https://www.statsmodels.org/)
StatsModels is a Python library built specifically for statistics. Statsmodels is built on top of NumPy, SciPy, and matplotlib, but it contains more advanced functions for statistical testing and modeling that you won't find in numerical libraries like NumPy or SciPy.

### [Plotly](https://plotly.com/)
Plotly enables Python users to create beautiful interactive web-based visualizations that can be displayed in Jupyter notebooks, saved to standalone HTML files, or served as part of pure Python-built web applications using Dash. I used this in `quantum-deutsch.ipynb` to display [chloropleth](https://plotly.com/python/choropleth-maps/) maps. 

### [SciPy](https://scipy.org/)
SciPy in Python is an open-source library used for solving mathematical, scientific, engineering, and technical problems. It allows users to manipulate the data and visualize the data using a wide range of high-level Python commands. SciPy is built on the Python NumPy extension.

### [Qiskit](https://qiskit.org/)
Qiskit is an open-source software development kit for working with quantum computers at the level of circuits, pulses, and algorithms. It provides tools for creating and manipulating quantum programs and running them on prototype quantum devices on IBM Quantum Experience or on simulators on a local computer. Using Qiskit, I simulate Deutsch's algorithm in `quantum-deutsch.ipynb` using Qiskit.

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
6. Open Terminal and type `$ python -V`. Python 3.9.0 should be displayed  

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
9. qiskit  
<br/>

For Windows:  
1. Open CMD
2. For each library type `pip install [library]`  
<br/>

For macOS:  
1. Open Terminal
2. For each library type `$ pip install [library]`  
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
2. Type `$ pip install jupyterlab`  
<br/>

For Other Platforms:  
1. Go to [Jupyter Lab installationn](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)  
<br>

### Installing via Anaconda
In order to install via Anaconda you must follow these steps in order. If you already have one of the steps completed, please move on to the next step.  
Steps:  
1. [Install Anaconda](#installing-anaconda)
2. [Install Jupyter](#installing-jupyter)

#### Installing Anaconda
For Windows:  
1. Go to [Anaconda](https://www.anaconda.com/products/individual#windows)
2. Click the [download](https://repo.anaconda.com/archive/Anaconda3-2021.11-Windows-x86_64.exe) button to download installer
3. Open installer which will guide you through the installation
4. Make sure to check the box which will add anaconda to PATH
5. Anaconda installed successfully
6. Open CMD and type `conda --version`. Your conda version should be displayed  
<br/>

For macOS:  
1. Go to [Anaconda](https://www.anaconda.com/products/individual)
2. Select "Get Additional Installers"
3. Select the [64-Bit Graphical Installer](https://repo.anaconda.com/archive/Anaconda3-2021.11-MacOSX-x86_64.pkg)
4. Open the installer and follow the instructions
5. Once installed we need tosource our .bash-rc file
6. Open Terminal and type `$ cd ~` followed by `$ source .bashrc`
7. Then type `$ python` and you should see something like `Python 3.9.0 | Anaconda Inc. |`  
<br/>

For Other Platforms:
1. Go to [Anaconda Installation](https://docs.anaconda.com/anaconda/install/linux/) and follow tutorial

#### Installing Jupyter
For Windows:  
1. Open CMD
2. Type `conda install jupyterlab`  
<br/>

For macOS:  
1. Open Terminal
2. Type `$ conda install jupyterlab`  
<br/>

For Other Platforms:  
1. Go to [Jupyter Lab installationn](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)  
<br>

## How to Run
The easiest way to view these notebooks is by clicking the badges below.  
You can view the `scikit-learn` and `quantum-deutsch` notebooks in static form by selecting the corresponding nbviewer
badge and in dynamic form by clicking the corresponding binder badge.

| Scikit-Learn | Quantum-Deutsch |
| :-: | :-:|
| [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/PatrickMurray78/emerging-tech/blob/main/scikit-learn.ipynb) | [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/PatrickMurray78/emerging-tech/blob/main/quantum-deutsch.ipynb) |
| [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PatrickMurray78/emerging-tech/main?filepath=scikit-learn.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PatrickMurray78/emerging-tech/main?filepath=quantum-deutsch.ipynb) |
<br>

If you would like to run using Jupyter Lab or Docker, the initial steps are the same.  
1. Open CMD or Terminal
2. Navigate to the folder you wish to clone this repo into
3. You may make a folder by typing `mkdir folderName`
4. Change directory to this folder by typing `cd folderName`
5. Once inside the folder, clone this repo by typing `git clone https://github.com/PatrickMurray78/emerging-tech`  
<br/>

### What Now?
1. [Run using Jupyer Lab](#how-to-run-using-jupyter-lab)
2. [Run using Docker](#how-to-run-using-docker)

### How to Run using Jupyter Lab
Once everything required has been installed, you may run Jupyter Lab by:
1. Open CMD or Terminal
2. Change directory to the repo we just downloaded. e.g `cd Users/folderName/emerging-tech`
3. Type `jupyter lab`. This will launch Jupyter Lab in the browser with all your notebooks and files

### How to Run using Docker
1. Open CMD or Terminal
2. Type `docker -v` to ensure docker is installed, if it is not then you may download it [here](https://docs.docker.com/get-docker/)
3. Change directory to the repo we just downloaded. e.g `cd Users/folderName/emerging-tech`
4. Run `docker-compose up`
5. Once deployed, copy the provided link and paste it as a URL
6. This will launch Jupyter Lab in the browser

# References
* Dr.Ian McLoughlin (Lecturer) https://github.com/ianmcloughlin
* Jupyter-Lab https://jupyter.org/
* Scikit-Learn https://scikit-learn.org/stable/
* NbViewer https://nbviewer.org/
  * NbViewer Badge https://github.com/jupyter/nbviewer/issues/714
* Binder https://mybinder.org/
* Docker https://docker.com/
