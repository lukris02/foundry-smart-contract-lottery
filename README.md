# Proveably Random Raffle Contracts

## Description
Verifiable random lottery contract. `Raffle.sol` contract allows for a fully automated lottery where users can buy a lottery ticket by entering a raffle. Functions like `checkUpkeep` and `performUpkeep` automate the lottery process, ensuring the system runs without manual intervention.

## Topics
Solidity, Foundry, Chainlink VRF v2.5, Chainlink Automation

# Getting Started

## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [foundry](https://getfoundry.sh/)

## Quickstart

```
git clone https://github.com/lukris02/foundry-smart-contract-lottery
cd foundry-smart-contract-lottery
forge build
```

## Deploy

This will default to your local node. You need to have it running in another terminal in order for it to deploy.

```
make deploy
```

## Testing

```
forge test
```
or

```
forge test --fork-url $SEPOLIA_RPC_URL
```
