# Cryptography Basics

## Summary  
Cryptography provides the foundation for blockchain security, ensuring integrity, authenticity, and confidentiality.  

## Key Points  

### Hash functions  
A hash function maps input data of any size to a fixed-length output.  
For blockchains, SHA-256 (Bitcoin) and Keccak-256 (Ethereum) are widely used.  
Hashes are one-way and collision-resistant, making them essential for verifying data integrity.  

### Public & private keys  
Each blockchain user has a private key (kept secret) and a public key (shared).   
The private key is used to sign transactions, while the public key allows others to verify the signature.  
This system underpins digital identity in Web3.  

### Digital signatures  
A digital signature proves that a transaction was created by the holder of the private key.  
It ensures authenticity (you are who you claim) and non-repudiation (you cannot deny sending it).  

### Wallets & addresses  
A wallet stores private keys and generates public addresses.  
An address is derived from the public key and acts as an identifier on the blockchain, like a bank account number.  

### Merkle trees  
Merkle trees allow efficient verification of large sets of data.  
Each leaf is a hash of data, and parent nodes are hashes of children.  
This lets nodes confirm a transaction belongs to a block without downloading the entire chain.  
