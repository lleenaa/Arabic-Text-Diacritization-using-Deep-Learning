# Arabic-Text-Diacritization-using-Deep-Learning

## Overview

This repository contains the Arabic Text Diacritization (ATD) project, which focuses on restoring diacritics to Arabic text using deep learning models.

## Project Description

Arabic Text Diacritization (ATD) is a vital task in Natural Language Processing (NLP) that involves placing diacritics on Arabic letters to clarify pronunciation and meaning. The project employs three different deep learning models for comparison:

1. Bidirectional LSTM (BiLSTM): Captures context from both past and future words using a recurrent neural network (RNN) architecture.

2. Feedforward Neural Network (FFNN): A simpler neural network model tested for comparison with BiLSTM.

3. Transformer-based Model: Utilizes attention mechanisms for efficient sequence modeling.
   

## Data Preprocessing

We performed extensive preprocessing to prepare the Arabic text for modeling, including:

* Removing diacritics from input text.

* Splitting text into manageable segments (max 500 characters).

* Cleaning text by removing non-Arabic characters, numbers, and punctuations.

* Mapping characters and diacritics using one-hot encoding.
  

## Dependencies

We utilized several pickle files for mappings, sourced from AliOsm GitHub Repository:

* 'ARABIC_LETTERS_LIST'

* 'DIACRITICS_LIST'

* 'RNN_SMALL_CHARACTERS_MAPPING'

* 'RNN_BIG_CHARACTERS_MAPPING'

* 'RNN_CLASSES_MAPPING'

* 'RNN_REV_CLASSES_MAPPING'


## Exploratory Data Analysis (EDA)

We conducted EDA to gain insights into the dataset, which included:

* Diacritics Frequency Analysis: Visualized the distribution of diacritics, with "Fatha" being the most frequent.

* Correlation Matrix: Explored relationships between diacritics using heatmaps.

* Word Cloud: Displayed the most frequent words in the dataset.

* Arabic Letters Frequency: Analyzed letter frequency using bar plots.

* Proportion of Text with Diacritics: Compared the percentage of text with full vs. minimal diacritics.
  

## Models Implemented

* Bidirectional LSTM (BiLSTM): Processes sequences in both directions for better context understanding.

* Feedforward Neural Network (FFNN): Simpler model, used for baseline comparison.

* Transformer-based Model: Utilizes self-attention for state-of-the-art performance.

