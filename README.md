# Symptom Entity Extraction and Linking

This repository contains Jupyter Notebooks for analyzing VAERS (Vaccine Adverse Event Reporting System) data using NLP techniques. The notebooks cover tasks such as data exploration, text similarity analysis, and visualization.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Data Preparation](#data-preparation)
- [Project Tasks](#project-tasks)
  - [Task 1: Data Exploration](#task-1-data-exploration)
  - [Task 2: Text Similarity Analysis](#task-2-text-similarity-analysis)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [References](#references)

### Introduction

This project involves working with VAERS data to perform various NLP tasks. The VAERS data includes records of adverse events reported following vaccinations.

### Setup

To run these notebooks, you will need to have the following dependencies installed:

- Python 3.x
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Seaborn
- NLTK

You can install the required packages using:

```bash
pip install tensorflow numpy pandas matplotlib seaborn nltk
```

### Data Preparation
- Download the VAERS data from the official VAERS website.
- Unzip the downloaded files.
- Place the .csv files in the ./Data/ directory.
- Update the data directory paths in the notebooks if necessary.

### Project Tasks
#### Task 1: Data Exploration
#### Notebook: NLP_Project_Task_1.ipynb

This notebook involves:

- Loading the VAERS data for the year 2020.
- Exploring and visualizing the data to understand its structure and contents.
- Performing preliminary data analysis and cleaning.
- Task 2: Text Similarity Analysis

#### Notebook: NLP_Project_Task_2_Similarity.ipynb

This notebook involves:

- Loading the VAERS data for multiple years.
- Preprocessing the text data for similarity analysis.
- Using NLP techniques to compute text similarity between reports.
- Visualizing the similarity results.

### Model Architecture
The notebooks utilize various NLP models and techniques such as tokenization, embedding, and similarity computation.

### Training
The notebooks include code for training NLP models if necessary. You can adjust the training parameters such as the number of epochs, batch size, and learning rate as needed.

### Evaluation
The model's performance is evaluated using metrics such as BLEU score, cosine similarity, or other relevant metrics to measure the quality of the NLP tasks.

### Results
Results and model performance will be displayed in the notebooks after training and evaluation.
