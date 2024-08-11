
# Contrastive Learning and Large Language Models for Depression Detection from Social Media

This project focuses on detecting depression-related emotions from social media posts using advanced machine learning (ML) and deep learning (DL) techniques, particularly Contrastive Learning with Large Language Models (LLMs) like BERT. The goal is to enhance the early and accurate detection of depression, which is crucial for timely intervention and better mental health outcomes.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Techniques and Models Used](#techniques-and-models-used)
- [Results](#results)

## Introduction

Depression is a pervasive mental health disorder, and its early detection is critical for effective intervention. With the rise of social media, platforms like Reddit and Twitter offer valuable data for analyzing depressive symptoms. This project explores the use of Contrastive Learning combined with LLMs to improve the detection of depression-related emotions from social media text data.

## Features

- **Advanced Text Analysis**: Utilizes NLP techniques to analyze social media posts and detect depression-related emotions.
- **State-of-the-Art Models**: Implements various ML and DL models, including SVM, LightGBM, XGBoost, GAN-BERT, BERT, BART, and Contrastive Learning with BERT.
- **Comprehensive Data Augmentation**: Enhances dataset diversity through techniques like synonym replacement, back translation, and noise injection.
- **Multilabel Classification**: Detects multiple co-occurring depressive emotions, reflecting the complex nature of depression.

## Dataset

The dataset used in this project is the **DepressionEmo** dataset, which comprises Reddit posts from mental health-related subreddits. The dataset is annotated with eight depression-related emotions:

- Anger
- Cognitive Dysfunction
- Emptiness
- Hopelessness
- Loneliness
- Sadness
- Suicide Intent
- Worthlessness

### Dataset Details

- **Total Examples**: 6,037 Reddit posts
- **Source**: Reddit posts from subreddits like r/depression, r/DepressedPartners, r/loneliness, r/suicide, and r/suicide_watch
- **Annotation Method**: Zero-shot classification validated by human and ChatGPT annotations

## Techniques and Models Used

### Machine Learning Models

- **Support Vector Machines (SVM)**
- **LightGBM**
- **XGBoost**

### Deep Learning Models

- **GAN-BERT**
- **BERT**
- **BART**

### Contrastive Learning

Contrastive Learning is employed to train models to distinguish between similar and dissimilar data points, enhancing the model’s ability to generalize and accurately detect subtle depression-related emotions.

## Results

The project evaluates the performance of various models using precision, recall, and F1 score. Below are some highlights:

- **BERT**: Achieved a strong performance with an F1 score of 0.74.
- **BART**: Outperformed other models with an F1 score of 0.76.
- **Contrastive Learning with BERT**: Achieved the highest F1 score of 0.81, demonstrating superior performance in detecting depression-related emotions.
