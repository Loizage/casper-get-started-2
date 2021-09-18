# Get started with Casper (Challange) Task #2

Task #1 Complete one of the existing tutorials for writing smart contracts

#### Used tutorials:
https://docs.casperlabs.io/en/latest/dapp-dev-guide/tutorials/counter/index.html
https://docs.casperlabs.io/en/latest/dapp-dev-guide/tutorials/counter/walkthrough.html

#### Full challenge report:
https://hackmd.io/@FLU_hhcJRUytCphhn38Cfg/Casper_get_started

## Counter Smart Contract

This is an example of a simple smart contract, the Counter.

## Usage

### Set up the Rust toolchain
You need the Rust toolchain to develop smart contracts.
```bash
$ make prepare
```

### Compile smart contracts
Compile WASM files that will be used later.
```bash
$ make build-contract
```
### Run tests
You can run integration tests with this command:
```bash
$ make test
```
