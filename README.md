# upgradeable-contracts
This repository includes a verified upgradeable contracts dataset and experimental results.

## RQ1
`./RQ1` contains the data and figure of the portion of posts about Upgradeable Smart Contracts.

## RQ2
### Verified upgradeable contracts dataset
`./RQ2/verified_dataset/verified_dataset.csv` contains 7,130 upgradeable contracts using proxy pattern and non-upgradeable contracts verified through manual verification.

### Experimental results and evaluation
- `./RQ2/cross validation` contains 5 models' cross-validation results.
- `./RQ2/Evaluation/5 models evaluation.csv` contains the raw data of Results of Predicting Upgradeable Contract Using Five Machine Learning Algorithm in the paper.

## RQ3
### Result of detection
- `./RQ3/metamorphic_redeploy_changed.csv` contains 28 metamorphic contracts with different codes redeployed. 
- `./RQ3/predicted_upgradeable.csv` contains 127,753 upgradeable contracts using the proxy pattern. Our method predicts these 127,753 upgradeable contracts out of 3,540,206 contracts that have made delegatecall transactions in Ethereum's first 12 million blocks.
