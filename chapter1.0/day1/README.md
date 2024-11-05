# Explain what the Blockchain is in your own words? You can read this to help you, but you don't have to: https://www.investopedia.com/terms/b/blockchain.asp

A blockchain is a distributed database or ledger shared across a computer network's nodes.

Examples include Bitcoin, Ethereum, Solana, and Flow. :)

# Explain what a Smart Contract is. You can read this to help you, but you don't have to: https://www.ibm.com/topics/smart-contracts

A smart contract is a computer program stored in a network like a blockchain that verifies and executes the performance of a contract (like a lawyer does) without the need for any trusted third party anywhere in the process, because the code itself is trusted.

# Explain the difference between a script and a transaction.


Script vs Transaction in Blockchain:
In the context of Bitcoin and blockchain technology, a script and a transaction serve distinct purposes.

Script: A script is a set of instructions, written in a stack-based programming language (Bitcoin Script), that defines the rules for spending or transferring funds in a specific way. Scripts are embedded in transactions and determine how the transaction’s outputs can be spent. They are used to:

Verify the authenticity of a transaction
Ensure that the transaction is valid according to specific conditions (e.g., specific public keys, signatures, or timestamps)
Define the recipient(s) of the transaction’s output(s)
Scripts can be simple or complex, and they are executed on the blockchain network by nodes when verifying transactions. There are various types of scripts, including:

Pay-to-Pubkey-Hash (P2PKH): A simple script that verifies a signature against a specific public key.
Pay-to-Script-Hash (P2SH): A script that allows multiple public keys to be used for spending.
Multi-Signature (MultiSig): A script that requires multiple signatures from different parties to authorize spending.
Transaction: A transaction, on the other hand, is a record of a value transfer between two or more parties on the blockchain network. It represents a single unit of data that contains:

Input(s): Previous transaction outputs being spent
Script: The set of instructions defining how the transaction’s outputs can be spent
Output(s): The new transaction outputs being created
Signature(s): Digital signatures verifying the transaction’s authenticity
Other metadata (e.g., timestamp, fee, and flags)
Transactions are broadcast to the network, verified by nodes, and grouped into blocks by miners. Each transaction has a unique hash, and the blockchain’s ledger (blockchain) records the entire history of transactions.

Key differences:

A script is a set of instructions, while a transaction is a record of a value transfer.
Scripts are embedded within transactions and define how outputs can be spent, whereas transactions contain the actual value transfer and metadata.
Scripts are executed on the blockchain network during transaction verification, whereas transactions are verified and recorded on the blockchain ledger.
In summary, scripts define the rules for spending or transferring funds, while transactions represent the actual value transfer between parties on the blockchain network.