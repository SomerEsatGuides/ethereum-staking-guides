# Ethereum Staking Guides - Change Log Archive#

## Mainnet Staking Guides ##

| Guide <img width=150/> | Change Log *(dd-mm-yy)* <img width=450/> |
| :--------- | :---------- |
| [Ubuntu/Lighthouse](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-lighthouse-773f5d982e03) | <br> *19-11-22* - Added `TimeoutStopSec=600` to Geth config. See [here](https://github.com/SomerEsat/ethereum-staking-guides/issues/6) for details. <br> *14-11-22* - Added required flag `--externalcl` to Erigon config. <br> *18-10-22* - Replaced Infura with [Checkpoint Sync Endpoints](https://eth-clients.github.io/checkpoint-sync-endpoints/). <br> *08-10-22* - Added `--prune-payloads` to Lighthouse service config. <br> *08-10-22* - Added `--logfile-max-number` & `--logfile-max-size` to Lighthouse service config. <br> *08-10-22* - Added `--Xplugin-rocksdb-high-spec-enabled` to Besu service config. <br> *08-10-22* - Added graffiti max 32 char limit note. <br> *08-10-22* - Removed section on merge. <br> *08-10-22* - Updated Besu, Erigon, Nethermind client versions. <br> *17-09-22* - Updated Erigon release to 2022.09.02. <br> *17-09-22* - Updated Geth release to 1.10.25. <br> *17-09-22* - Updated Nethermind release to 1.14.2. <br> *11-09-22* - Updated Besu service config to use 4GB RAM (-Xmx4g). <br> *08-09-22* - Updated Besu release to 22.7.2. <br> *08-09-22* - Updated Nethermind release to 1.14.1. <br> *06-09-22* - Updated Erigon release to 2022.09.01. <br> *01-09-22* - Updated Lighthouse release to 3.1.0.<br> *28-08-22* - Updated Erigon release to 2022-08-03-Alpha. <br> *27-08-22* - Added missing `chown` step. <br> *24-08-22* - Updated Geth release to 1.10.23. <br> *24-08-22* - Added link to the [supplementary guide](https://someresat.medium.com/supplementary-guide-to-staking-on-ethereum-for-existing-stakers-57493678a460). <br> *23-08-22* - Added "A Note on the Merge" section. <br> *22-08-22* - Merge-Ready version published. <br> *26-11-20* - Beacon Chain Genesis version published. |
| [Ubuntu/Lodestar](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-lodestar-193a2553a161) | <br> *19-11-22* - Added `TimeoutStopSec=600` to Geth config. See [here](https://github.com/SomerEsat/ethereum-staking-guides/issues/6) for details. <br> *14-11-22* - Added required flag `--externalcl` to Erigon config. <br> *18-10-22* - Replaced Infura with [Checkpoint Sync Endpoints](https://eth-clients.github.io/checkpoint-sync-endpoints/). <br> *08-10-22* - Added `--Xplugin-rocksdb-high-spec-enabled` to Besu service config. <br> *08-10-22* - Added graffiti max 32 char limit note. <br> *08-10-22* - Removed section on merge. <br> *08-10-22* - Updated Besu, Erigon, Nethermind client versions. <br> *17-09-22* - Updated Erigon release to 2022.09.02. <br> *17-09-22* - Updated Geth release to 1.10.25. <br> *17-09-22* - Updated Nethermind release to 1.14.2. <br> *11-09-22* - Updated Besu service config to use 4GB RAM (-Xmx4g). <br> *08-09-22* - Updated Nimbus release to 22.9.0. <br> *08-09-22* - Updated Besu release to 22.7.2. <br> *08-09-22* - Updated Nethermind release to 1.14.1. <br> *06-09-22* - Updated Erigon release to 2022.09.01. <br> *01-09-22* - Updated Nimbus release to 22.8.2. <br> *30-08-22* - Updated Nimbus release to 22.8.1. <br> *28-08-22* - Updated Erigon release to 2022-08-03-Alpha. <br> *24-08-22* - Updated Geth release to 1.10.23. <br> *24-08-22* - Added link to the [supplementary guide](https://someresat.medium.com/supplementary-guide-to-staking-on-ethereum-for-existing-stakers-57493678a460). <br> *23-08-22* - Added "A Note on the Merge" section. <br> *22-08-22* - Merge-Ready version published. <br> *26-11-20* - Beacon Chain Genesis version published. |
| [Ubuntu/Nimbus](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-nimbus-31f56657ea8f) | <br> *19-11-22* - Added `TimeoutStopSec=600` to Geth config. See [here](https://github.com/SomerEsat/ethereum-staking-guides/issues/6) for details. <br> *14-11-22* - Added required flag `--externalcl` to Erigon config. <br> *18-10-22* - Updated Nimbus logo and release to 22.10.1. <br> *18-10-22* - Replaced Infura with [Checkpoint Sync Endpoints](https://eth-clients.github.io/checkpoint-sync-endpoints/). <br> *08-10-22* - Added `--Xplugin-rocksdb-high-spec-enabled` to Besu service config. <br> *08-10-22* - Added graffiti max 32 char limit note. <br> *08-10-22* - Removed section on merge. <br> *08-10-22* - Updated Besu, Erigon, Nethermind client versions. <br> *17-09-22* - Updated Erigon release to 2022.09.02. <br> *17-09-22* - Updated Geth release to 1.10.25. <br> *17-09-22* - Updated Nethermind release to 1.14.2. <br> *11-09-22* - Updated Besu service config to use 4GB RAM (-Xmx4g). <br> *08-09-22* - Updated Nimbus release to 22.9.0. <br> *08-09-22* - Updated Besu release to 22.7.2. <br> *08-09-22* - Updated Nethermind release to 1.14.1. <br> *06-09-22* - Updated Erigon release to 2022.09.01. <br> *01-09-22* - Updated Nimbus release to 22.8.2. <br> *30-08-22* - Updated Nimbus release to 22.8.1. <br> *28-08-22* - Updated Erigon release to 2022-08-03-Alpha. <br> *24-08-22* - Updated Geth release to 1.10.23. <br> *24-08-22* - Added link to the [supplementary guide](https://someresat.medium.com/supplementary-guide-to-staking-on-ethereum-for-existing-stakers-57493678a460). <br> *23-08-22* - Added "A Note on the Merge" section. <br> *22-08-22* - Merge-Ready version published. <br> *26-11-20* - Beacon Chain Genesis version published. |
| [Ubuntu/Prysm](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-prysm-581fb1969460) | <br> *19-11-22* - Added `TimeoutStopSec=600` to Geth config. See [here](https://github.com/SomerEsat/ethereum-staking-guides/issues/6) for details. <br> *14-11-22* - Added required flag `--externalcl` to Erigon config. <br> *18-10-22* - Replaced Infura with [Checkpoint Sync Endpoints](https://eth-clients.github.io/checkpoint-sync-endpoints/). <br> *08-10-22* - Added `--Xplugin-rocksdb-high-spec-enabled` to Besu service config. <br> *08-10-22* - Added graffiti max 32 char limit note. <br> *08-10-22* - Removed section on merge. <br> *08-10-22* - Updated Besu, Erigon, Nethermind client versions. <br> *17-09-22* - Updated Erigon release to 2022.09.02. <br> *17-09-22* - Updated Geth release to 1.10.25. <br> *17-09-22* - Updated Nethermind release to 1.14.2. <br> *11-09-22* - Updated Besu service config to use 4GB RAM (-Xmx4g). <br> *08-09-22* - Updated Besu release to 22.7.2. <br> *08-09-22* - Updated Nethermind release to 1.14.1. <br> *06-09-22* - Updated Erigon release to 2022.09.01. <br> *05-09-22* - Updated Prysm release to 3.1.0. <br> *28-08-22* - Updated Erigon release to 2022-08-03-Alpha. <br> *27-08-22* - Added missing `chown` step. <br> 26-08-22 - Added `suggested-fee-recipient` to validator config. <br> *24-08-22* - Updated Geth release to 1.10.23. <br> *24-08-22* - Added link to the [supplementary guide](https://someresat.medium.com/supplementary-guide-to-staking-on-ethereum-for-existing-stakers-57493678a460). <br> *23-08-22* - Replaced `--http-web3provider` with `--execution-endpoint`. <br> *23-08-22* - Added "A Note on the Merge" section. <br> *22-08-22* - Merge-Ready version published. <br> *27-11-20* - Beacon Chain Genesis version published. |
| [Ubuntu/Teku](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-teku-f09ecd9ef2ee) | <br> *19-11-22* - Added `TimeoutStopSec=600` to Geth config. See [here](https://github.com/SomerEsat/ethereum-staking-guides/issues/6) for details. <br> *14-11-22* - Added required flag `--externalcl` to Erigon config. <br> *18-10-22* - Replaced Infura with [Checkpoint Sync Endpoints](https://eth-clients.github.io/checkpoint-sync-endpoints/). <br> *08-10-22* - Added `--Xplugin-rocksdb-high-spec-enabled` to Besu service config. <br> *08-10-22* - Added graffiti max 32 char limit note. <br> *08-10-22* - Removed section on merge. <br> *08-10-22* - Updated Besu, Erigon, Nethermind client versions. <br> *19-09-22* - Updated Teku release to 22.9.1. <br> *17-09-22* - Updated Erigon release to 2022.09.02. <br> *17-09-22* - Updated Geth release to 1.10.25. <br> *17-09-22* - Updated Nethermind release to 1.14.2. <br> *11-09-22* - Updated Besu service config to use 4GB RAM (-Xmx4g). <br> *08-09-22* - Updated Besu release to 22.7.2. <br> *08-09-22* - Updated Nethermind release to 1.14.1. <br> *06-09-22* - Updated Erigon release to 2022.09.01. <br> *01-09-22* - Updated Teku release to 22.9.0. <br> *30-08-22* - Updated Teku release to 22.8.2. <br> *28-08-22* - Updated Erigon release to 2022-08-03-Alpha. <br> *24-08-22* - Updated Geth client version to 1.10.23. <br> *24-08-22* - Added link to the [supplementary guide](https://someresat.medium.com/supplementary-guide-to-staking-on-ethereum-for-existing-stakers-57493678a460). <br> *23-08-22* - Added "A Note on the Merge" section. <br> *22-08-22* - Merge-Ready version published. <br> *26-11-20* - Beacon Chain Genesis version published. |

<br/>

## Goerli Testnet Staking Guides ##

| Guide <img width=150/> | Change Log *(dd-mm-yy)* <img width=450/> |
| :---- | :--------- |
| [Ubuntu/Lighthouse](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-g%C3%B6erli-lighthouse-8d0a2a811e6e) | Published 06-08-22, Updated 19-11-22 |
| [Ubuntu/Lodestar](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-goerli-lodestar-f3c8f77e7097) | Published 10-09-22, Updated 19-11-22 |
| [Ubuntu/Prysm](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-goerli-prysm-4a640794e8b5) | Published 07-08-22, Updated 19-11-22 |
| [Ubuntu/Nimbus](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-goerli-nimbus-3b0e2c0c6e0e) | Published 06-08-22, Updated 19-11-22 |
| [Ubuntu/Teku](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-g%C3%B6erli-teku-6512b26f1372) | Published 06-08-22, Updated 19-11-22 |

<br/>

## Mainnet Migration Guides (Not Merge Ready - Updates Pending) ##

| Guide <img width=150/> | Change Log *(dd-mm-yy)* <img width=450/> |
| :---- | :--------- |
| [Series Introduction](https://someresat.medium.com/ethereum-staker-migration-guides-introduction-45505079b1f0) | Published 12-04-22 |
| [Migrating from Prysm to Nimbus](https://someresat.medium.com/ethereum-staker-migration-guide-migrating-from-prysm-to-nimbus-b802a7dcb31e) (NOT Merge Ready)| Published 11-05-22 |
| Migrating from Prysm to Teku - coming soon! | |
| Migrating from Prysm to Lodestar - coming soon! | |
| Migrating from Prysm to Lighthouse - coming soon! | |
| Series Conclusion - coming soon! | |