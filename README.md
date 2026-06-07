# explainable-fuzzy-aviation-occurrences
# Explainable AI with Evolutionarily Optimized Fuzzy Systems for Aviation Occurrence Classification

This repository contains the experimental pipelines developed for the paper:

**Explainable Artificial Intelligence Based on Evolutionarily Optimized Fuzzy Systems Applied to the Classification of Aviation Occurrences**

## Overview

This project proposes a hybrid approach based on Decision Trees, Fuzzy Logic, and Genetic Fuzzy Systems (GFS) for the explainable classification of aviation occurrences recorded in a public dataset provided by the Brazilian Aeronautical Accidents Investigation and Prevention Center (CENIPA).

The main objective is not to maximize predictive performance, but to transform complex patterns identified in aviation data into explicit, interpretable, and auditable knowledge.

## Methodological Workflow

The methodology follows four main stages:

1. Data Engineering and Exploratory Data Analysis (EDA);
2. Knowledge Extraction using an Interpretable Decision Tree;
3. Translation of Decision Tree Rules into Fuzzy Linguistic Rules;
4. Evolutionary Optimization of the Fuzzy Rule Base using Genetic Fuzzy Systems.

## Repository Structure

```text
notebooks/

├── 01_data_engineering_and_eda.ipynb
├── 02_decision_tree_modeling.ipynb
├── 03_decision_tree_to_fuzzy_rules.ipynb
└── 04_mamdani_gfs_optimization.ipynb
```

## Dataset

The experiments were conducted using public aviation occurrence data provided by CENIPA (Brazilian Aeronautical Accidents Investigation and Prevention Center).

The original datasets can be obtained directly from the Brazilian Open Data Portal.

## Main Results

* Interpretable Decision Tree with 8 explicit rules;
* Mamdani Fuzzy Inference System derived from Decision Tree knowledge;
* Genetic Fuzzy System optimization reducing the rule base from 8 to 5 rules;
* Improved knowledge representation and interpretability;
* Analysis of the trade-off between predictive performance, interpretability, and computational cost.

## Research Context

This work extends research originally developed within the Database Systems Engineering and Administration Specialization Program at the School of Technology (FT), University of Campinas (UNICAMP), Brazil.

## Authors

Felipe Pedroso de Lima Brusse

Guilherme Palermo Coelho

## License

This repository is intended for academic and research purposes.
