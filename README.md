# Text Classification Models

This repository contains two text classification models implemented in Python: **Multinomial Naive Bayes** and **Support Vector Machine (SVM)**. These models are designed to classify news articles into various categories.

## Table of Contents

- [Overview](#overview)
- [Models](#models)
  - [Multinomial Naive Bayes](#multinomial-naive-bayes)
  - [Support Vector Machine (SVM)](#support-vector-machine-svm)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Overview

Text classification is a crucial task in natural language processing (NLP) that involves assigning predefined categories to text documents. This repository demonstrates two effective models for classifying news articles.

## Models

### Multinomial Naive Bayes

- **Description**: This model uses the Multinomial Naive Bayes algorithm, which is well-suited for text classification tasks, especially with word frequency features.
- **Notebook**: [multinomial_naive_bayes.ipynb](./multinomial_naive_bayes.ipynb)

### Support Vector Machine (SVM)

- **Description**: The SVM model employs a kernel-based approach to classify data points in a high-dimensional space, making it effective for text classification.
- **Notebook**: [svm.ipynb](./svm.ipynb)

## Installation

To run the notebooks, ensure you have the following packages installed in your Python environment:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/ahmdmohamedd/text-classification-models.git
   cd text-classification-models
   ```

2. Open the Jupyter Notebook for the desired model:

   ```bash
   jupyter notebook multinomial_naive_bayes.ipynb
   # or
   jupyter notebook svm.ipynb
   ```

3. Follow the instructions in the notebooks to preprocess data, train the models, and evaluate their performance.

## Results

The performance of both models is evaluated using metrics such as accuracy, precision, recall, and F1-score. Results are displayed in the respective notebooks, along with visualizations.
