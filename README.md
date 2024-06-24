# Explaining Hate

## Overview

Our project aims to accurately classify social media posts into categories of of-
fensive, hate, or normal speech. Unlike typical toxicity detectors that only label
comments as toxic or not, we have developed a model that differentiates between
these three types of speech and identifies the specific communities targeted by
the post.
Disclaimer: The article contains material that many will find offensive or hate-
ful; however, this cannot be avoided due to the nature of the project

## Installation Instructions

Follow these steps to set up the environment and install the necessary dependencies.

#### Using Conda

1. Create and activate a conda environment.
2. Install `ipykernel`.
3. Install the packages listed in `requirements.txt`.

#### Using Virtualenv (Python Environment)

1. Create and activate a virtual environment.
2. Install `ipykernel`.
3. Install the packages listed in `requirements.txt`.

## Code Explanation

### model-nlp_final.ipynb

This notebook contains all the code necessary for running the project. It includes data preprocessing, model loading, and testing.

### distilbert Folders

These folders contain the trained DistilBERT models used in the project. Each folder includes the necessary files to load and use the models.

### BirRNN.pth Files

These are the trained Bi-directional RNN models. There are two `BirRNN.pth` files, each representing a different trained model.

## Instructions to Execute the Code

1. **Preprocessing**: Run all the preprocessing cells in the notebook to prepare the data.
2. **Initial BERT Models**: Execute the initial part of the notebook that involves loading the BERT models.
3. **Skip Training**: Skip the training sections in the notebook.
4. **Loading and Testing**: Run the cells under "Loading and Testing" to test the models.
5. **Multilabel Processing**: For the multilabel part, again skip only the training section and proceed with the rest.
6. **BiRNN Models**: Run all the section except the training subsection, and remove the "#" from the load models block to effectively load the pretrained model (probably # already removed)
