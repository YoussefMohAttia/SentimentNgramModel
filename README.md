<div align="center">

# Sentiment N-gram Models

### Classical NLP Models for Review and Sentence-Level Sentiment Analysis

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![scikit--learn](https://img.shields.io/badge/scikit--learn-NLP-F7931E?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)

</div>

## Overview

This repository collects two NLP assignment notebooks focused on sentiment classification with n-gram features. The work moves from language-model and n-gram foundations to supervised classifiers evaluated with standard classification metrics.

## Notebooks

- `Part1.ipynb` explores token processing, n-gram modeling, counts, and probability calculations.
- `Part2.ipynb` implements and evaluates multinomial Naive Bayes and logistic-regression sentiment classifiers, including from-scratch learning routines and scikit-learn comparisons.
- `sst.py` provides supporting utilities for the Stanford Sentiment Treebank workflow.

## Evaluation

The second notebook calculates accuracy, precision, recall, F1 score, and confusion matrices for the trained classifiers.

## Getting Started

```bash
python -m venv .venv
source .venv/bin/activate
pip install jupyter numpy scikit-learn matplotlib seaborn
jupyter notebook
```

Run `Part1.ipynb` and `Part2.ipynb` independently from top to bottom. Consult `assignment 1.pdf` for the original task specification.

## Author

**Youssef Mohamed Attia**  
[GitHub](https://github.com/YoussefMohAttia) · [LinkedIn](https://www.linkedin.com/in/youssefmohattia/)
