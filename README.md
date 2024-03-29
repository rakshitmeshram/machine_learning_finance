# ML for Finance

 In this project, under the guidance of Dr. Kushal Kr. Shah, at the Indian Institute of Science Education and Research, Bhopal, we aim to classify financial instruments into one of sector based categories. We will use a dataset that contains various financial indicators such as price, volume, and volatility. We will develop a multi-class classification model using Support Vector Machines (SVM), Random Forest, K-Nearest Neighbor and Multilayer Neural Network to predict the company's category.

## Overview

Problems Attempted : 
* **Sectorwise Classification.ipynb** : This file shows a multiclass classification of NIFTY 50 companies sector-wise using daily stock data which can be used by a beginner in Machine Learning as a starter to get an idea of structuring a complete Machine Learning project including data collection (unlike competitions), data cleaning and making a prediction model on it.


## Downloading Data

The stock data used here, is of the companies on the NIFTY 50 index, National Stock Exchange of India's benchmark broad based stock market index for the Indian equity market, which has been dowloaded using the [Quandl](https://www.quandl.com) API, and the ticker symbols of the companies from [wiki](https://en.wikipedia.org/wiki/NIFTY_50). To train the models on some other company data, search for those companies on Quandl and grab their QuandlCodes and replace the eisting codes with them. e.g. **the QuandlCode for the company "Adaniports" is "NSE/ADANIPORTS" where NSE stands for National Stock Exchange**. 

## Requirements and Installation

In order to run these scripts, you'll need the following libraries.
* [Tensorflow](https://www.tensorflow.org/install/) 
* [Pandas](https://pandas.pydata.org/pandas-docs/stable/install.html)
* [Numpy](https://docs.scipy.org/doc/numpy/user/install.html)
* [Scikit-learn](https://scikit-learn.org/stable/install.html)
* [Quandl](https://www.quandl.com/tools/python) with a free and email-verified account
* [Seaborn](https://seaborn.pydata.org/installing.html)
* [Matplotlib](https://matplotlib.org/users/installing.html)

**The easiest way to install TensorFlow as well as all the other libraries is to start with the Anaconda Python distribution**.

### Installing Anaconda Python and TensorFlow

  1. Follow the [installation instructions for Anaconda](https://conda.io/docs/user-guide/install/windows.html) Python. We recommend using Python 3.6.

  2. Follow the platform-specific [TensorFlow installation instructions](https://www.tensorflow.org/install/). Be sure to follow the "Installing with Anaconda" process, and create a Conda environment named `tensorflow`.

  3. If you aren't still inside your Conda TensorFlow environment, enter it by opening your terminal and typing 
     
     ```
     source activate tensorflow
     ```
  
  4. If you haven't done so already, download and unzip this entire repository from GitHub, either interactively, or by entering 
     
     ```
     git clone https://github.com/RakshitMeshram/ML-for-Finance
     ```
     
  5. Use `cd` to navigate into the top directory of the repo on your machine

  6. Launch Jupyter by entering
  
     ```
     jupyter notebook
     ```
     
     and, using your browser, navigate to the URL shown in the terminal output (usually http://localhost:8888/)
