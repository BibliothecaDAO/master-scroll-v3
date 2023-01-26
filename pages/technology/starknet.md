# StarkNet & Validity Proofs
---

The Ethereum Virtual Machine (EVM) is a powerful tool for developing decentralized applications, but it is not well-suited for heavy computation, which is a common requirement for games. To enable the creation of true on-chain realities and worlds, a new technology is needed. One such technology that shows great promise for this purpose is STARKs (Scalable Transparent Argument of Knowledge).

StarkNet is a validity proof generalized smart contract network that allows anyone to publish smart contracts. These smart contracts create small proofs, which are then validated by external machines. Once enough of these proofs have been created by the network, a batch is published onto the Ethereum mainnet. This approach enables the heavy computation required for games to be abstracted, while still retaining the security guarantees of a decentralized network, like Ethereum. This technology will enable the creation of more complex and engaging games that can run on a decentralized network, and it will pave the way for new types of on-chain realities and worlds.


## STARKS

### What is a STARKS
"ZK-STARKs (Zero-Knowledge Scalable Transparent ARguments of Knowledge) are a type of cryptographic proof technology that enables users to share validated data or perform computations with a third party without the data or computation being revealed to the third-party, also known as a zero-knowledge proof, in a way that is publicly verifiable. In simpler terms, a zero-knowledge proof can prove something is true without having to reveal what exactly it is proving. For example, ZK-STARKs would allow Alice to verify Bob's banking information using a zero-knowledge cryptographic proof instead of revealing the confidential information to Alice."

https://docs.ethhub.io/ethereum-roadmap/layer-2-scaling/zk-starks/

### What is StarkNet 
StarkNet is a permissionless decentralized Validity-Rollup (also known as a “ZK-Rollup”), operating as an L2 network over Ethereum. It enables greatly enhanced scaling for its computation –  without compromising Ethereum’s composability and security, thanks to StarkNet’s reliance on the safest and most scalable cryptographic proof system (STARKs). StarkNet has been developed by StarkWare Industries Ltd, the pioneers behind the StarkEx scalability engine.

![StarkNet](static/img/starknet.png)
*Source:* StarkWare Industries

### Scalable and computational 
STARKs are able to improve the scalability of an L1 network by allowing developers to move computations and (in the future) storage off-chain. Off-chain services can generate STARK proofs that attest the integrity of off-chain computations. These proofs are then published on-chain for any interested party to validate the computation. In completing the bulk of computational work off-chain with STARKs, existing blockchain infrastructure can scale exponentially while still trustlessly maintaining computational integrity.

### Cairo and a new way to write contracts
Solidity has a number of limitations that make it inefficient for compiling STARKS, such as relying on more inefficient data structures (e.g uint256) and limited access to low-level primitives. Cairo is the first Turing-complete language for creating provable programs for general computation, enabling these limitations be bypassed. 

