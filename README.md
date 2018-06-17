# Ethereum Walkthrough {#ethereum-walkthrough}

_This is a work in progress. Comments and suggestions are welcome._

This is a brief walkthrough of some of the core source files for smart contracts in the official [Go language](https://golang.org/) Ethereum implementation, which includes the [`geth`](https://github.com/ethereum/go-ethereum/tree/master/core/vm) command-line Ethereum client program, along with many other programs. Ethereum clients include an implementation of the Ethereum Virtual Machine \(EVM\), which are able to parse and verify the Ethereum blockchain, including smart contracts, and provides interfaces to create transactions and mine blocks.

I've added some suggestions for how the source code might be improved. If there is general agreement that these suggestions make sense \(tell me in the comments!\) then I'll create a pull request.

