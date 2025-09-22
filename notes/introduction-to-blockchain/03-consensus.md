# Consensus Mechanisms

## Summary  
Consensus algorithms allow a decentralised network to agree on the state of the blockchain.  

## Key Points  

### Proof of Work (PoW)  
Used by Bitcoin, PoW requires miners to solve complex cryptographic puzzles.  
The first to solve adds the block and earns rewards.  
While secure, it is energy-intensive and slow, making it less scalable.  

### Proof of Stake (PoS)  
Validators stake tokens to secure the network.  
Instead of competing with computation, validators are randomly chosen to propose blocks.  
Misbehaviour can result in slashing (losing stake).  
PoS is faster and energy-efficient.  

### Other models  
- **Delegated PoS (DPoS)**: Token holders elect a small group of validators. Used in EOS.  
- **Proof of Authority (PoA)**: Validators are pre-approved entities. Used in private/consortium blockchains.  
- **Byzantine Fault Tolerance (BFT)**: Consensus by majority agreement, often used in smaller networks.  

### Why consensus matters  
Consensus ensures the network agrees on a single version of the ledger.  
Without it, blockchains would face double-spending, forks, or malicious manipulation.  

