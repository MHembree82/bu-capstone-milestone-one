# ICU Delirium Screening: Milestone One

Notebooks and data for Milestone One of my Boston University MS in Data Science capstone (Module C). The project is an early warning model for ICU delirium. I tested six modeling techniques on two datasets and compared them with repeated cross validation.

## Datasets
- MIMIC-IV Clinical Database Demo (100 patients, 140 ICU stays): predicts ICU length of stay and a positive CAM-ICU delirium screen. The feature table is delirium_features.csv.
- E-CAM-S (373 patients, 1189 EEG features): predicts CAM-S severity and a delirium call. Data from the Brain Data Science Platform (MIT license), in the ecams folder.

## Notebooks
- Wk1: polynomial and interaction terms
- Wk2: ridge, lasso, elastic net
- Wk3: forward and backward selection, PCR, PLSR
- Wk4: logistic regression and feature scaling
- Wk5: support vector machines
- Wk6: decision trees and random forests
- Wk7: summary notebook that puts every technique from Weeks 1 to 6 on the same footing, with the figures used in the paper
- Wk8: earlier second dataset (Pima diabetes), replaced in the paper by E-CAM-S
- SecondDataset-ECAMS: all six techniques on E-CAM-S, the second dataset used in the paper

## Running it
Install pandas, numpy, scikit-learn, matplotlib, and seaborn, keep the csv files in the same folder as the notebooks, and run the cells in order.
