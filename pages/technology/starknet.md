---
sidebar_position: 2
description: The Ethereum L2 STARK scalability solution
---

# StarkNet & Validity Proofs
---

Games are some of the most complex pieces of software that exist in the world. The Ethereum Virtual Machine (EVM) is an incredible tool for low power requirement software, however it is not suited for heavy computation (and was never designed for it). For true on-chain realities and worlds to emerge we require a new technology, and we believe that STARKS show the greatest promise to achieve this.

StarkNet is a validity proof generalized smart contract network in which anyone can publish smart contracts. These smart contracts create tiny proofs which are validated by external machines. Once enough of these proofs have been created by the network a batch is published onto Ethereum Mainnet. This enables the heavy computation needed for games to be abstracted, while still retaining the security guarantee of a decentralized network, Ethereum.


## STARKS

### What is a STARKS
"ZK-STARKs (Zero-Knowledge Scalable Transparent ARguments of Knowledge) are a type of cryptographic proof technology that enables users to share validated data or perform computations with a third party without the data or computation being revealed to the third-party, also known as a zero-knowledge proof, in a way that is publicly verifiable. In simpler terms, a zero-knowledge proof can prove something is true without having to reveal what exactly it is proving. For example, ZK-STARKs would allow Alice to verify Bob's banking information using a zero-knowledge cryptographic proof instead of revealing the confidential information to Alice."

https://docs.ethhub.io/ethereum-roadmap/layer-2-scaling/zk-starks/

### What is StarkNet 
StarkNet is a permissionless decentralized Validity-Rollup (also known as a “ZK-Rollup”), operating as an L2 network over Ethereum. It enables greatly enhanced scaling for its computation –  without compromising Ethereum’s composability and security, thanks to StarkNet’s reliance on the safest and most scalable cryptographic proof system (STARKs). StarkNet has been developed by StarkWare Industries Ltd, the pioneers behind the StarkEx scalability engine.

![StarkNet](/static/img/starknet.png)
*Source:* StarkWare Industries

### Scalable and computational 
STARKs are able to improve the scalability of an L1 network by allowing developers to move computations and (in the future) storage off-chain. Off-chain services can generate STARK proofs that attest the integrity of off-chain computations. These proofs are then published on-chain for any interested party to validate the computation. In completing the bulk of computational work off-chain with STARKs, existing blockchain infrastructure can scale exponentially while still trustlessly maintaining computational integrity.

### Cairo and a new way to write contracts
Solidity has a number of limitations that make it inefficient for compiling STARKS, such as relying on more inefficient data structures (e.g uint256) and limited access to low-level primitives. Cairo is the first Turing-complete language for creating provable programs for general computation, enabling these limitations be bypassed. 

### Account Abstraction
Ethereum is limited to two types of accounts: Externally Owned Accounts (EOA) and Contract Accounts (CA). User accounts - EOAs - are tied to a specific cryptographic signer, which must be used in order to execute transactions. StarkNet removes this limitation - and instead accounts are smart contracts that can define their own logic in how it interacts with the network. This provides exciting possibilites for gaming, such as guild account contracts and authenticating with session keys to open a secure game state that doesn't require constant signing of transactions. The potential of account abstraction will greatly enhance blockchain gaming as it is fully explored in the years to come. 