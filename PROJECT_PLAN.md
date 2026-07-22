# SleepGuard AI – Project Plan

> Advanced Practical Machine Learning Project
>
> Master 2 – Data Engineering & Cloud Computing
>
> Aivancity 2025-2026

---

# 1. Project Overview

## Objective

The objective of this project is to build an end-to-end Deep Learning application capable of predicting an individual's **Sleep Disorder Risk** based on demographic, physiological, behavioral, and environmental factors.

The final solution will include:

- Data exploration
- Data preprocessing
- Feature engineering
- A Deep Learning model implemented with PyTorch
- Model evaluation
- A Streamlit web application
- Technical report
- Final presentation video

---

# 2. Problem Statement

Poor sleep quality is associated with several physical and mental health issues.

Healthcare professionals often rely on multiple indicators to evaluate sleep disorders.

Our objective is to investigate whether a Deep Learning model can accurately predict the level of sleep disorder risk using lifestyle and health-related information.

---

# 3. Dataset

Dataset selected:

**sleep_health_dataset.csv**

Main target variable:

> sleep_disorder_risk

Target classes:

- Healthy
- Mild
- Moderate
- Severe

Potential input features include:

- Age
- Gender
- BMI
- Occupation
- Country
- Sleep Duration
- Sleep Latency
- REM Sleep %
- Deep Sleep %
- Caffeine Consumption
- Alcohol Consumption
- Screen Time
- Physical Activity
- Daily Steps
- Stress Score
- Mental Health Condition
- Heart Rate
- Room Temperature
- Chronotype
- Shift Work
- Season

The final feature selection will be decided after the exploratory data analysis.

---

# 4. Project Roadmap

## Phase 1 — Exploratory Data Analysis (EDA)

Objectives

- Understand the dataset
- Identify missing values
- Study feature distributions
- Analyze target distribution
- Detect correlations
- Detect outliers

Deliverables

- EDA notebook
- Data visualization

---

## Phase 2 — Data Preprocessing

Objectives

- Handle missing values
- Encode categorical variables
- Normalize numerical features
- Split training and testing datasets

Deliverables

- Clean dataset
- Preprocessing pipeline

---

## Phase 3 — Feature Engineering

Objectives

- Evaluate feature importance
- Remove unnecessary features
- Create new features if relevant

Deliverables

- Optimized dataset

---

## Phase 4 — Deep Learning Model

Objectives

Build a neural network using PyTorch.

Possible architecture:

Input Layer

↓

Hidden Layer 1

↓

Hidden Layer 2

↓

Output Layer

Tasks

- Define architecture
- Select activation functions
- Select loss function
- Select optimizer
- Train the model
- Save the best model

Deliverables

- Trained PyTorch model (.pth)

---

## Phase 5 — Model Evaluation

Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Deliverables

- Evaluation report
- Performance visualizations

---

## Phase 6 — Streamlit Application

Features

### Home

Project presentation

### Dataset Insights

- Dataset overview
- Statistics
- Charts

### Prediction

User enters personal information.

The application predicts:

- Sleep Disorder Risk
- Prediction confidence

### Model Performance

Display:

- Accuracy
- Confusion Matrix
- Classification Report

### About

Project description and disclaimer.

---

## Phase 7 — Documentation

Deliverables

- README
- Technical report (3–5 pages)
- Architecture diagram
- Installation guide

---

## Phase 8 — Final Presentation

Presentation should explain:

- Dataset
- EDA
- Feature Engineering
- Neural Network
- Training
- Results
- Streamlit Demo

Each team member must be able to explain every part of the implementation.

---

# 5. Proposed Technologies

Programming Language

- Python

Libraries

- PyTorch
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Streamlit

Development Environment

- Jupyter Notebook
- VS Code
- GitHub

---

# 6. Expected Repository Structure

```
Advanced-Practical-Machine-Learning-Project
│
├── Datasets/
├── notebooks/
├── src/
│   ├── preprocessing.py
│   ├── dataset.py
│   ├── model.py
│   ├── train.py
│   ├── evaluate.py
│   └── predict.py
│
├── models/
│   └── best_model.pth
│
├── app/
│   └── streamlit_app.py
│
├── report/
│
├── README.md
└── PROJECT_PLAN.md
```

---

# 7. Team Discussion Points

Before implementation, the team should validate:

- Is Sleep Disorder Risk the best prediction target?
- Which features should be kept or removed?
- Which neural network architecture should be used?
- How should the Streamlit application be organized?
- How should the work be divided between both team members?

---

# 8. Current Status

✅ Dataset selected

✅ Project idea validated

⬜ Exploratory Data Analysis

⬜ Data Preprocessing

⬜ Feature Engineering

⬜ Deep Learning Model

⬜ Evaluation

⬜ Streamlit Application

⬜ Technical Report

⬜ Final Video Presentation

---

# Notes

This document represents the initial project planning.

It may evolve throughout the project after discussions, experimentation, and feedback from the instructor.