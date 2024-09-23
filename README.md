# Multilabel Classification in Large-Scale Text Datasets: A Data-Driven and Model-Driven Approach

This repository contains the notebooks for a project focused on multilabel classification using both data-driven and model-driven approaches.

## Project Overview

The project compares multiple models to solve the challenge of classifying large-scale text data with multiple labels. It investigates both traditional machine learning models and transformer-based architectures, as well as the impact of grouping labels to improve performance.

## Repository Structure

- `01_data_understanding_and_preprocessing.ipynb`: Covers text preprocessing steps such as stopword removal, lemmatization, and label binarization.
- `02_model_training.ipynb`: Implements and trains several models, including Logistic Regression, SVM, and DistilBERT, comparing their performance on the task.
- `03_model_evaluation.ipynb`: Evaluates and compares the performance of all models, examining the effect of label grouping on classification results.

## Usage

To run the notebooks, simply load them into Jupyter or Colab and ensure the dataset paths are correctly configured.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
