# Individual-Assignment-4

 Lecture 04 Individual Assignment
 DNSC 6330: Responsible Machine Learning


# Assignment 
*From Accuracy to Accountability: Stress Testing a Predictive Model**

---

# Overview
This notebook extends the COMPAS recidivism risk scoring pipeline built across Lectures 01–03 to evaluate whether the models remain reliable, fair, and generalizable beyond the training setting. The analysis covers distribution drift, generalization, spurious correlations, robustness under stress, and slice-based fairness evaluation.




#Parts Completed

| Part | Topic | Methods Used |
|------|-------|-------------|
| A | Distribution Drift | PSI, KS test, MMD² |
| B | Generalization & Overfitting | Train/test AUC gap, permutation importance |
| C | Spurious Correlation Probe | Counterfactual attribute swaps |
| D | Robustness & Stress Testing | Stress test on `priors_count`, ICE curves, sensitivity index |
| E | Slice-Based Evaluation | Performance by race, gender, age, and crime type |

Each part includes code, outputs, and a written markdown interpretation.

---
