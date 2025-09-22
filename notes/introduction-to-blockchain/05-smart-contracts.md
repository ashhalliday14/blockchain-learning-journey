# Smart Contracts  

## Summary  
Smart contracts are self-executing programs deployed on blockchains, enabling trustless automation.  

## Key Points  

### Solidity basics  
Solidity is Ethereum’s main programming language.  
It is statically typed, influenced by JavaScript and C++, and compiles to EVM bytecode.  
Contracts can store data, define logic, and interact with other contracts.  

### Lifecycle  
1. Write contract in Solidity.  
2. Compile into bytecode.  
3. Deploy to the blockchain.  
4. Interact using transactions or external apps.  

### Standards  
- **ERC-20**: Fungible tokens (e.g. stablecoins, governance tokens).  
- **ERC-721**: Non-Fungible Tokens (NFTs).  
- **ERC-1155**: Multi-token standard for both fungible and non-fungible assets.  

### Security considerations  
- **Reentrancy attacks** (e.g. The DAO hack).  
- **Integer overflow/underflow** (fixed in Solidity 0.8+).  
- **Access control** (only owner functions).  
Auditing and testing are essential to prevent losses.  

