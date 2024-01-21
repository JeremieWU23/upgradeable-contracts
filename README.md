# upgradeable-contracts
This repository includes a verified upgradeable contracts dataset and experimental results.

## RQ1
`./RQ1` contains the data and figure of the portion of posts about Upgradeable Smart Contracts.

## RQ2
### Verified upgradeable contracts dataset
`./RQ2/verified_dataset/algo1.py` is the algorithm to detect potential proxy upgradeable contracts.
`./RQ2/verified_dataset/verified_potential_4455.csv` contains 4,455 potential proxy upgradeable contracts.
`./RQ2/verified_dataset/verified_dataset_with_opcodes_8704.csv` contains 8,704 verified contracts(4,352 upgradeable contracts using proxy pattern and 4,352 non-upgradeable contracts).

### Experimental results and evaluation
- `./RQ2/cross validation` contains the best model's cross-validation results.
- `./RQ2/Evaluation/5_models_evaluation.csv` contains the raw data of Results of Predicting Upgradeable Contract Using Five Machine Learning Algorithm in the paper.

## RQ3
### Result of detection
- `./RQ3/metamorphic_redeploy_changed.csv` contains 28 metamorphic contracts with different codes redeployed. 
