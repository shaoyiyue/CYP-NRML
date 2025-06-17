# CYP-NRML: CYP inhibition prediction under non-random missing labels 

This repository contains the dataset and source code accompanying the paper:

**Learning from Incomplete Labels: A Non-Random
Missingness-Aware LLM Framework for Drug
Interaction Prediction**

##  Overview

Cytochrome P450 (CYP) enzymes play a critical role in drug metabolism. Predicting whether a chemical compound inhibits one or more CYP isoforms is essential for early-stage drug screening and safety profiling. This project provides:

- A curated multi-label inhibition dataset across five major CYP isoforms
- evaluation tools
- Support for training LLM-based models under Non-Random Missing Labels (NRML)

## Dataset Summary

The dataset covers five CYP isoforms:
- **CYP1A2**
- **CYP2C9**
- **CYP2C19**
- **CYP2D6**
- **CYP3A4**

Each compound is annotated with:
- SMILES representation
- Binary inhibition labels (active/inactive) for isoform
- A multi-label inhibition  **non-random missingness**



