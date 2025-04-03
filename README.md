## NLP
Assignment for Natural Language Processing Class, 1º Year,2º Semester, Masters in Artificial Intelligence

This repository contains an implementation of NLP classifiers for a multilabel text classification task using the "RePro-categories-multilabel" dataset. The project focuses on building traditional machine learning models to categorize product reviews into labels such as "ENTREGA", "PRODUTO", "ANUNCIO", etc., without employing deep learning architectures (e.g., CNNs, RNNs, or Transformers).

### Project Overview
Objective: Develop and evaluate NLP classifiers using techniques covered in the course, including pre-processing, feature extraction (sparse and dense representations), and traditional classifiers (e.g., Logistic Regression, SVM, XGBoost).
Dataset: The dataset, sourced from Hugging Face [higopires/RePro-categories-multilabel](https://huggingface.co/datasets/higopires/RePro-categories-multilabel), consists of Portuguese reviews with 6 labels, collected and annotated to reflect various aspects of product feedback.
### Techniques:
Pre-processing includes text normalization, lemmatization, and stemming with removal of stop words.
Feature extraction involves TF-IDF (sparse) and Word2Vec (dense) representations.
Classifiers implemented include Linear SVM, Multinomial Naive Bayes, and XGBoost with a custom One-vs-Rest approach for multilabel classification.
Evaluation: Models are assessed using metrics like Precision, Recall, F1-score (macro and micro), and Hamming Loss, with error analysis to understand misclassifications.

### Authors:
* Marta Pereira
* Ana Azevedo
* Mafalda Aires
