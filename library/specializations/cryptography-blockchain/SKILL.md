---
name: specialization-cryptography-blockchain
description: "Cryptography and Blockchain Development is a specialized domain focused on building secure, decentralized systems using cryptographic primitives, distributed ledger technology, and smart contract platforms. This specialization encompasses the design, implementation, and auditing of blockchain…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: cryptography-blockchain
  process-count: 33
---

# specialization-cryptography-blockchain

## Overview

Cryptography and Blockchain Development is a specialized domain focused on building secure, decentralized systems using cryptographic primitives, distributed ledger technology, and smart contract platforms. This specialization encompasses the design, implementation, and auditing of blockchain protocols, smart contracts, zero-knowledge proof systems, decentralized finance (DeFi) applications, and Web3 infrastructure.

## Available Processes (33)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/cryptography-blockchain/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `amm-pool-development` (`specializations/cryptography-blockchain/amm-pool-development`) | AMM Pool Development - Implementation of automated market maker liquidity pools with constant product or custom |
| `blockchain-indexer-development` (`specializations/cryptography-blockchain/blockchain-indexer-development`) | Blockchain Indexer Development - Development of blockchain indexers for event tracking, state aggregation, |
| `blockchain-node-setup` (`specializations/cryptography-blockchain/blockchain-node-setup`) | Blockchain Node Setup and Operation - Setup and configuration of blockchain nodes for various networks |
| `bug-bounty-program` (`specializations/cryptography-blockchain/bug-bounty-program`) | Bug Bounty Program Setup - Setup and management of bug bounty programs for smart contract security |
| `cross-chain-bridge` (`specializations/cryptography-blockchain/cross-chain-bridge`) | Cross-Chain Bridge Development - Development of secure cross-chain bridges for asset transfers between |
| `cryptographic-protocol-implementation` (`specializations/cryptography-blockchain/cryptographic-protocol-implementation`) | Cryptographic Protocol Implementation - Secure implementation of cryptographic protocols including signature |
| `dapp-frontend-development` (`specializations/cryptography-blockchain/dapp-frontend-development`) | dApp Frontend Development - Development of decentralized application frontends with wallet integration, |
| `economic-simulation` (`specializations/cryptography-blockchain/economic-simulation`) | Economic Simulation - Agent-based economic simulations for DeFi protocols to analyze tokenomics, |
| `erc1155-multi-token` (`specializations/cryptography-blockchain/erc1155-multi-token`) | ERC-1155 Multi-Token Implementation - Development of multi-token contracts supporting both fungible and |
| `erc20-token-implementation` (`specializations/cryptography-blockchain/erc20-token-implementation`) | ERC-20 Token Implementation - Development process for creating secure, standard-compliant ERC-20 fungible tokens |
| `erc4626-tokenized-vault` (`specializations/cryptography-blockchain/erc4626-tokenized-vault`) | ERC-4626 Tokenized Vault Development - Implementation of yield-bearing vault tokens following the ERC-4626 |
| `erc721-nft-collection` (`specializations/cryptography-blockchain/erc721-nft-collection`) | ERC-721 NFT Collection Development - End-to-end process for developing NFT collections including metadata design, |
| `formal-verification` (`specializations/cryptography-blockchain/formal-verification`) | Formal Verification of Smart Contracts - Mathematical verification of smart contract properties using formal |
| `gas-optimization` (`specializations/cryptography-blockchain/gas-optimization`) | Gas Optimization Process - Systematic optimization of smart contract gas consumption through code refactoring, |
| `governance-system` (`specializations/cryptography-blockchain/governance-system`) | Governance System Implementation - On-chain governance implementation with proposal creation, voting mechanisms, |
| `hd-wallet-implementation` (`specializations/cryptography-blockchain/hd-wallet-implementation`) | HD Wallet Implementation (BIP-32/39/44) - Implementation of hierarchical deterministic wallets with mnemonic |
| `incident-response-exploits` (`specializations/cryptography-blockchain/incident-response-exploits`) | Incident Response for Exploits - Structured incident response process for smart contract exploits |
| `invariant-testing` (`specializations/cryptography-blockchain/invariant-testing`) | Invariant Testing - Comprehensive invariant testing for DeFi protocols to ensure system properties hold |
| `lending-protocol` (`specializations/cryptography-blockchain/lending-protocol`) | Lending Protocol Implementation - Development of over-collateralized lending and borrowing protocols with |
| `multi-signature-wallet` (`specializations/cryptography-blockchain/multi-signature-wallet`) | Multi-Signature Wallet Development - Development of multi-signature wallets requiring M-of-N approvals for |
| `privacy-token-implementation` (`specializations/cryptography-blockchain/privacy-token-implementation`) | Privacy Token Implementation - Implementation of privacy-preserving tokens using ZK proofs for |
| `smart-contract-development-lifecycle` (`specializations/cryptography-blockchain/smart-contract-development-lifecycle`) | Smart Contract Development Lifecycle - End-to-end process for developing secure smart contracts from requirements |
| `smart-contract-fuzzing` (`specializations/cryptography-blockchain/smart-contract-fuzzing`) | Smart Contract Fuzzing - Fuzzing smart contracts using tools like Echidna and Foundry for property-based |
| `smart-contract-security-audit` (`specializations/cryptography-blockchain/smart-contract-security-audit`) | Smart Contract Security Audit Process - Systematic security review of smart contracts including manual code review, |
| `smart-contract-upgrade` (`specializations/cryptography-blockchain/smart-contract-upgrade`) | Smart Contract Upgrade Process - Safe upgrade process for proxy-based upgradeable contracts including storage |
| `staking-contract` (`specializations/cryptography-blockchain/staking-contract`) | Staking Contract Development - Implementation of token staking mechanisms with reward distribution, |
| `subgraph-development` (`specializations/cryptography-blockchain/subgraph-development`) | Subgraph Development - Development of subgraphs for The Graph protocol to index blockchain events |
| `threshold-signature-scheme` (`specializations/cryptography-blockchain/threshold-signature-scheme`) | Threshold Signature Scheme Implementation - Implementation of threshold cryptography for distributed key |
| `validator-node-operation` (`specializations/cryptography-blockchain/validator-node-operation`) | Validator Node Operation - Setup and operation of proof-of-stake validator nodes with key management, |
| `yield-aggregator` (`specializations/cryptography-blockchain/yield-aggregator`) | Yield Aggregator Development - Development of automated yield optimization protocols that allocate capital |
| `zk-circuit-development` (`specializations/cryptography-blockchain/zk-circuit-development`) | ZK Circuit Development (Circom/Noir) - Development of zero-knowledge circuits using Circom or Noir for |
| `zk-rollup-development` (`specializations/cryptography-blockchain/zk-rollup-development`) | ZK-Rollup Development - Development of zero-knowledge rollup solutions for Ethereum scalability with |
| `zk-snark-application` (`specializations/cryptography-blockchain/zk-snark-application`) | ZK-SNARK Application Development - Development of ZK-SNARK-based applications with trusted setup ceremonies, |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `cryptography-blockchain` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
