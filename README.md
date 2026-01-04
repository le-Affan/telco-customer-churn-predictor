# Telco Churn Classification

End-to-end tabular classification project focused on execution maturity rather than model novelty.

This project is part of a pre-flagship ML execution phase and emphasizes correct workflow, decision-making, evaluation discipline, and shipping a usable ML system.

## Objectives
- Handle messy real-world tabular data
- Make and own ML decisions
- Apply correct preprocessing and evaluation discipline
- Perform meaningful error analysis
- Build a minimal but real inference system

## Problem Statement
Predict whether a telecom customer will churn based on customer demographics, account information, and service usage.

Target variable:
- Churn (Yes / No)

This is a supervised binary classification problem using classical machine learning.

## Dataset
Telco Customer Churn dataset  
Source: Public telecom churn dataset (Kaggle)

Characteristics:
- Mixed numerical and categorical features
- Noisy real-world structure
- Requires preprocessing and careful evaluation

## Project Structure
data/
├── raw/                # original dataset
├── processed/          # cleaned / transformed data (if created)

notebooks/
├── main.ipynb          # EDA, experimentation, decision-making

src/
├── train.py            # training pipeline (later)
├── evaluate.py         # evaluation logic (later)
├── inference.py        # inference / serving logic (later)

README.md
.gitignore


## Workflow Discipline
The project strictly follows this order:
1. Dataset selection
2. Problem framing and target definition
3. Train / validation / test split
4. Baseline model
5. First proper model
6. Evaluation
7. Error analysis
8. Capacity increase (if justified)
9. Final evaluation
10. Minimal applied ML system

## Status
Currently in execution phase.
Pipeline is being built step by step with strict workflow control.
