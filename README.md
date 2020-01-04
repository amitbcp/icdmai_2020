# A Recurrent Neural Pipeline for Multi-Class | Multi-Label Text Classification


This repository walks you through an end-to-end  flow of training  Sequence Models (RNNs) along with all the tips/tricks/pointers of which a developer should be aware.

Here, we explain how to frame/handle a Multi-Class | Multi-Label Text Classification problem statement along with it's data preparation pipeline.

## Quick Start

### Want to play with these notebooks online without having to install anything?
Use any of the following services.

**WARNING**: Please be aware that these services provide temporary environments: anything you do will be deleted after a while, so make sure you download any data you care about.

* **Recommended**: open this repository in [Colaboratory](https://github.com/amitbcp/icdmai_2020/tree/master):
<a href="https://colab.research.google.com/github/amitbcp/icdmai_2020/blob/master/"><img src="https://colab.research.google.com/img/colab_favicon.ico" width="90" /></a>


### Just want to quickly look at some notebooks, without executing any code?

Browse this repository using [jupyter.org's notebook viewer](https://github.com/amitbcp/icdmai_2020/tree/master/README.md):
<a href="https://github.com/amitbcp/icdmai_2020/tree/master/README.md"><img src="https://jupyter.org/assets/nav_logo.svg" width="150" /></a>

_Note_: [github.com's notebook viewer](index.ipynb) also works but it is slower and the math equations are not always displayed correctly.

## Problem Statement
Given a post/question from Stackoverflow, predict the Technology Domain & Associated Tags for it.
We are working with a only 14 Technology Domain & 112 Tags . Less than 10% data from Stackoverflow questions are used for demonstration purpose only.

The Technology domains are :

1. Programming
2. MS-Development Environment
3. Server Side Development
4. Mobile App Development
5. Dev Environment
6. Front-end/Designing
7. Dynamic UI
8. MVC
9. Dev Ops
10. Big Data
11. QA
12. Project Management
13. Scripting
14. Business Analytics


## Notebooks

1. [Exploratory Data Analysis](https://github.com/amitbcp/icdmai_2020/blob/master/1_eda.ipynb) : Explore the relationships within different groups and labels with the text.
2. [Classical ML Approach](https://github.com/amitbcp/icdmai_2020/blob/master/2_classical_ml_approach.ipynb) : Demonstrate Naive Baise, SVM  & Logistic Regression for baseline modeling.
3. Data Preparation :  Creating dataset for RNNs
   a. [Standard](https://github.com/amitbcp/icdmai_2020/blob/master/3a_standard_data_preparation.ipynb) : Creating group level dataset without handling biasness.
   b. [Normalise](https://github.com/amitbcp/icdmai_2020/blob/master/3b_normalise_data_preparation.ipynb) : Creating group level dataset after clipping data to  normalise the distribution.
4. [Word Embedding](https://github.com/amitbcp/icdmai_2020/blob/master/4_word_embedding.ipynb) : Training Custom word-embeddings for our corpus
5. [Model Training](https://github.com/amitbcp/icdmai_2020/blob/master/5_model_training.ipynb) : Prototyping & Training LSTMs for Text Classification
6. [Inference Pipeline](https://github.com/amitbcp/icdmai_2020/blob/master/6_inference_pipeline.ipynb) : Ensembling models for prediction
7. [Visualise Results](https://github.com/amitbcp/icdmai_2020/blob/master/7_visualize_results.ipynb) : Plotting Loss curves & perfomance metrics
8. [Outline]() : Handling RNN pipelines end-to-end.
9. [Proposal](https://github.com/amitbcp/icdmai_2020/blob/master/proposal_icdmai_2020.pdf) : Proposal to ICDMAI 2020 committee
