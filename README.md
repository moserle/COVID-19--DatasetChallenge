# COVID-19--DatasetChallenge
The following repository contains a submission for the 'COVID-19 Open Research Dataset Challenge (CORD-19) ' on Kaggle as well as a Sentiment Analysis for COVID-19 medications.  
This work was part of a project for the course 'Machine Learning For Health Care' at ETH Zurich and was done by Levin Moser, Julia Ortheden and Rafael Bischof.

## Overview
The 'COVID-19-DatasetChallenge.ipynb' contains a submission to the kaggle challenge.  
In 'Medications Sentiment Analysis.ipynb' we further did a Medications Sentiment Analysis.

## Running The Project
Clone the repository.

### Install the Conda environment 
```console
conda env create -f ml4hc.yml
conda activate ml4hc
```

### Download the Data
Download the following zip file and unzip it directly into the repository folder:
https://polybox.ethz.ch/index.php/s/Jkio7nE13xaoK0l 

### Run the notebooks
```console
jupyter notebook COVID-19-DatasetChallenge.ipynb
```
or 
```console
jupyter notebook Medications Sentiment Analysis.ipynb
```