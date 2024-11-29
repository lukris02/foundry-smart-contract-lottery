# Proveably Random Raffle Contracts

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