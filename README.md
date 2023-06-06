# upgradeable-contracts
This repository includes a verified upgradeable contracts dataset and experimental results.

## Verified upgradeable contracts dataset
In `./dataset/verified_dataset`, `verified_dataset.csv` contains 7,130 upgradeable contracts using proxy pattern and non-upgradeable contracts verified through manual verification.


## Experimental results

In `./dataset/detection_results`, `metamorphic_redeploy_changed.csv` contains 28 metamorphic contracts with different codes redeployed. 

`predicted_upgradeable.csv` contains 127,753 upgradeable contracts using the proxy pattern. Our method predicts these 127,753 upgradeable contracts out of 3,540,206 contracts that have made delegatecall transactions in the first 12 million blocks of Ethereum.
