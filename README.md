# Blockchain-Ledger
> Description

This python programs demonstrates a simplified blockchain network used to keep track of trades made by brokers for their clients.
We have implemented Zero Knowledge Proof (Discrete Log) to verify users. The Brokers are pre-defined, although new users can be registered.
The block is mined using a difficulty. The hash of a block is calculated using SHA256 and DES.

> Files

main.py - Main function of the code
Block.py - Class file for Blockchain block
Record.py - Class file for storing data within the block
User.py - Class file for user
DES.py, DES_assets.py - Implementation of DES
users.txt, brokers.txt, records.txt, blockchain.txt - Simplified database files
