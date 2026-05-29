# complete-reentrancy-attack

This repository contains small Solidity examples for studying reentrancy attacks.

Each folder focuses on one variant of the issue:

- `classic` for the original single-contract reentrancy pattern
- `cross-function` for reentrancy that moves through another function in the same contract
- `cross-contract` for reentrancy that passes through multiple contracts
- `read-only` for reentrancy that exploits inconsistent reads during state changes

Each example folder will contain:

- a vulnerable contract that demonstrates the attack surface
- a solution contract that shows one way to prevent or mitigate the issue

## How to use this repo

Open the folder for the attack type you want to study, then read the vulnerable contract first and compare it with the solution contract.

The repository is intentionally minimal at this stage so the examples can be expanded step by step in the article.