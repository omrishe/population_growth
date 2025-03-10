# Population Growth Prediction

## Overview

This project is a Python-based web scraping and machine learning application that predicts next year's population growth in different cities.
It utilizes Selenium to crawl websites for demographic data, processes and stores the extracted information, and applies machine learning models to forecast population trends.

## Features

Web Scraping with Selenium: Automatically collects population-related data from online sources.

Data Processing: Cleans, structures, and stores the extracted data.

Machine Learning Model: Uses historical data to train a model and predict population growth for the upcoming year.

Data Visualization: Graphs and charts for better understanding of trends.

## Tech Stack

Python (Primary language)

Selenium (Web scraping)

Pandas, NumPy (Data processing)

Scikit-Learn (Machine learning)

Matplotlib, Seaborn (Visualization)

SciPy (Statistical analysis)

Bidi (Bidirectional text handling for right-to-left languages)

## Installation

Clone this repository:

git clone https://github.com/omrishe/population_growth
cd population_growth

### Install dependencies:

pip install pandas         
pip install requests
pip install numpy
pip install bs4
pip install selenium
pip install webdriver-manager
pip install  bidi
pip install  matplotlib
pip install  seaborn
pip install  scipy
pip install  scikit-learn


Download a Selenium WebDriver (e.g., ChromeDriver) and place it in your system path.

Run the scraper:

crawling.ipynb

run the data handeling and machine learning:
data-handling and machine learning.ipynb

## Usage

you can either rescrape the data or use the data already scrapped (updated 2022)

Ensure you have the correct WebDriver installed and configured.

Example Output

A dataset with past and predicted population growth.

Graphs showing growth trends.

and info about each variable depending on year

at the end its possible to see how far the prediction model deviated from the actual results

Future Improvements

Expand the dataset by adding more sources.

Implement deep learning techniques for better accuracy.

Create a web interface for easy access to predictions.


## Authors: omri shema, nir tzameret

