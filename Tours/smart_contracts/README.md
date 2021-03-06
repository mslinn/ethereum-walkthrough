## Tour: Smart Contracts {#smart-contracts}

The `core/vm` directory contains the files that implement the EVM. These files are part of the `vm` package. We will look at two of them:

* [`contract.go`](https://github.com/ethereum/go-ethereum/blob/master/core/vm/contract.go), which defines smart contract behavior.
* [`contracts.go`](https://github.com/ethereum/go-ethereum/blob/master/core/vm/contracts.go), responsible for executing smart contracts on the EVM.

Before we dig into those source files, we will first look at the types that they use.

