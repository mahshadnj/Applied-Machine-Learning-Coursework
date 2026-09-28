# Final Project — Cerebral Palsy Gait Pattern Classification

## Overview

This project investigates the use of supervised machine learning
for classifying sagittal-plane gait patterns in children with
cerebral palsy according to the Rodda classification system.

The main objective is not only to evaluate classification performance,
but also to investigate the relative contribution of the hip, knee,
and ankle joints to gait-pattern discrimination.

Four Rodda gait patterns are considered:

- True Equinus
- Jump Gait
- Apparent Equinus
- Crouch Gait

## Dataset

The dataset contains sagittal-plane kinematic joint-angle trajectories
from children with cerebral palsy.

Each sample contains 300 kinematic features:

- 100 time-normalized samples for the hip joint
- 100 time-normalized samples for the knee joint
- 100 time-normalized samples for the ankle joint

Each sample is assigned to one of the four Rodda gait-pattern classes.

## Joint-Wise Analysis

Seven different joint configurations were evaluated:

1. Hip
2. Knee
3. Ankle
4. Hip + Knee
5. Hip + Ankle
6. Knee + Ankle
7. Hip + Knee + Ankle

This joint-wise analysis was used to investigate how individual joints
and combinations of joints contribute to gait-pattern classification.

## Machine Learning Models

The following supervised learning algorithms were evaluated:

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest (RF)
- Logistic Regression (LR)

Hyperparameters were optimized using cross-validation.

## Preprocessing

The analysis pipeline includes:

- Outlier detection using Z-scores
- Stratified train/test splitting
- Feature standardization
- Class balancing using SMOTE
- Hyperparameter tuning using cross-validation

## Exploratory Analysis

Before classification, the kinematic data were explored using:

- Mean joint-angle trajectories across the gait cycle
- Principal Component Analysis (PCA)
- Joint-wise and combined feature-space visualization

## Evaluation

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrices

## Main Findings

Classification performance improved as information from additional
joints was included.

Among the individual joints, the knee provided the strongest
discriminative information. Combining the knee and ankle substantially
improved classification performance, while the best results were
obtained when all three joints were used.

The results suggest that Rodda gait patterns are inherently
multi-joint and that combining biomechanical information from
different lower-limb joints improves their discrimination.

## Files

- `cp-gait-classification.ipynb` — complete analysis and machine learning pipeline
- `data/cp-gait-kinematics.csv` — kinematic dataset used for classification
- `report/final-project-report.pdf` — complete project report
