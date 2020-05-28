# CoNLL 2003 Tagger

This repo contains a tagger on CoNLL2003 dataset. The data contains three files, training set, testing set and validation set. The data contains POS tags, Chunk tags and Named Entity Tags. No pre-trained model and no pre-trained embedding have been used. All three tagging tasks have been done using Bi-LSTM models. 
The data can be found [here](https://github.com/patverga/torch-ner-nlp-from-scratch/tree/master/data/conll2003).

## Pre-requisites

Use requirements.txt file to install the required packages. You could also create a new environment using this file.

```bash
pip install -r requirements.txt
```

## Usage

After downloading/cloning this repo, open your terminal. Change directory to the root of the repo and run the following to see the Jupyter Notebooks.

```bash
jupyter notebook conll2003_analysis.ipynb
```

## Files

The data files are in a folder called "data". All other files are in the root.


## Version
Python 3.7.1

## Author
Upasana Parashar