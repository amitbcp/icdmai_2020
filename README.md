# A Recurrent Neural Pipeline for Multi-Class | Multi-Label Text Classification


This repository walks you through an end-to-end  flow of training  Sequence Models (RNNs) along with all the tips/tricks/pointers of which a developer should be aware.

Here, we explain how to frame/handle a Multi-Class | Multi-Label Text Classification problem statement along with it's data preparation pipeline.

## Quick Start

### Want to play with these notebooks online without having to install anything?
Use any of the following services.

**WARNING**: Please be aware that these services provide temporary environments: anything you do will be deleted after a while, so make sure you download any data you care about.

* **Recommended**: open this repository in [Colaboratory](https://colab.research.google.com/github/ageron/handson-ml2/blob/master/):
<a href="https://colab.research.google.com/github/ageron/handson-ml2/blob/master/"><img src="https://colab.research.google.com/img/colab_favicon.ico" width="90" /></a>


### Just want to quickly look at some notebooks, without executing any code?

Browse this repository using [jupyter.org's notebook viewer](https://nbviewer.jupyter.org/github/ageron/handson-ml2/blob/master/index.ipynb):
<a href="https://nbviewer.jupyter.org/github/ageron/handson-ml2/blob/master/index.ipynb"><img src="https://jupyter.org/assets/nav_logo.svg" width="150" /></a>

_Note_: [github.com's notebook viewer](index.ipynb) also works but it is slower and the math equations are not always displayed correctly.

## Problem Statement

## Notebooks

1. [Exploratory Data Analysis]() : Explore the relationships within different groups and labels with the text.
2. [Classical ML Approach]() : Demonstrate Naive Baise, SVM  & Logistic Regression for baseline modeling.
3. Data Preparation :  Creating dataset for RNNs
   a. [Standard]() : Creating group level dataset without handling biasness.
   b. [Normalise]() : Creating group level dataset after clipping data to  normalise the distribution.
4. [Word Embedding]() : Training Custom word-embeddings for our corpus
5. [Model Training]() : Prototyping & Training LSTMs for Text Classification
6. [Inference Pipeline]() : Ensembling models for prediction
7. [Visualise Results]() : Plotting Loss curves & perfomance metrics
8. [Outline]() : Handling RNN pipelines end-to-end.
9. [Proposal]() : Proposal to ICDMAI 2020 committee
