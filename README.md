# TV-script-generation

## Table of Contents

1. [Project Overview](#project_overview)
2. [Installation](#installation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Overview <a name="project_overview"></a>

In this project, I generated Seinfeld TV scripts using RNNs based on part of the [Seinfeld dataset](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv) of scripts from 9 seasons. The LSTM RNN model will generate a new ,"fake" TV script, based on patterns it recognizes in this training data.

## Installation <a name="installation"></a>

Required libraries and packages can be find in the [requirement file]('requirement.txt')

## File Descriptions <a name="files"></a>

### Folders: 
**Data:** contains the original data file: [Seinfeld_Scripts.txt]('/Data/Seinfeld_Scripts.txt')

### Files:
**dlnd_tv_script_generation.ipynb:** the main notebook for the TV script generation

**dlnd_tv_script_generation.html:** html format of dlnd_tv_script_generation.ipynb

**helper.py:** contains functions used the main notebook

**preprocess.p:** precleaned dataset (Punctuation tokenized, Words to ints using Bag of Words)

**problem_unittests.py:** contains unit test functions used the main notebook

## Results<a name="results"></a>

Using the 2-layer neural network with 24 node hidden layer, 5000 epochs and 0.2 learning rate, the final training MSE loss is 0.056 and the final validation MSE loss is 0.160.
The predicted results are gievn below:

<img src="assets/result.png" />

## Licensing, Authors, and Acknowledgements<a name="licensing"></a>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Acknowledge to [Udacity](https://www.udacity.com/) for providing the stater code.  





