# bitcoin-mining-python

What Is Bitcoin Mining?

Bitcoin mining is the process of verifying bitcoin transactions and recording them in the public blockchain ledger. In blockchain, the transactions are verified by bitcoin users, so basically the transactions have to be verified by the participants of the network. Those who have the required hardware and computing power are called miners.

We will talk more about them later, but the important concept to understand here is that there is nothing like a centralized body—a regulatory body, a governing body, a bank—to make bitcoin transactions go through. Any user with mining hardware and Internet access can be a participant and contribute to the mining community.

The process is solved based on a difficult mathematical puzzle called proof of work. The proof of work is needed to validate the transaction and for the miner to earn a reward. All the miners are completing amongst themselves to mine a particular transaction; the miner who first solves the puzzle gets the reward. Miners are the network participants who have the necessary hardware and computing power to validate the transactions.

3 Concepts of Blockchain

To understand bitcoin mining, you have to first understand the three major concepts of blockchain.

Public distributed ledger: A distributed ledger is a record of all transactions maintained in the blockchain network across the globe. In the network, the validation of transactions is done by bitcoin users.
SHA-256: Blockchain prevents unauthorized access by using a hash function called SHA-256 to ensure that the blocks are kept secure. They are digitally signed. Their hash value, once generated, cannot be altered. SHA-256 takes an input string of any size and returns a fixed 256-bit output, and it is a one-way function—you cannot derive the reverse of the input reverse fully from the output (what you have generated).
Proof of work: In blockchain mining, miners validate transactions by solving a difficult mathematical puzzle called proof of work. To do that, the primary objective of the miner is to determine the nonce value, and that nonce value is the mathematical puzzle that miners are required to solve to generate a hash that is less than the target defined by the network for a particular block.

Bitcoin Mining Explained
By Shivam Arora
Last updated on Apr 1, 202134169
Bitcoin Mining Explained
Since its introduction in 2009 by Satoshi Nakamoto, bitcoin has excited investors, tech pros and everyday people alike. Even celebrities like Mike Tyson have gotten involved; the former pro boxer has launched both a bitcoin ATM and a bitcoin wallet app. But you don’t have to be any kind of a pro to understand how bitcoin works.



Simplilearn’s video tutorial explains the process of bitcoin mining and the advantages of bitcoin over traditional fiat currencies. First, we’ll cover some basics about bitcoin, and then we’ll discuss how bitcoin mining works.

Equip yourself with the structure and mechanism of Bitcoin by enrolling for the Blockchain Certification Training Course today!
What Is Bitcoin?
Bitcoin is the first decentralized digital currency that allows peer-to-peer transfers without any intermediaries such as banks, governments, agents or brokers, using the underlying technology of blockchain. Anyone around the world on the network can transfer bitcoins to someone else on the network regardless of geographic location; you just need to just open an account on the Bitcoin network and have some bitcoins in it, and then you can transfer those bitcoins. How do you get bitcoins in your account? You can either purchase them online or mine them.

Bitcoin can be used for online purchases and can be used as an investment instrument. Primarily it’s used to buy goods and services.

Bitcoin Advantages
Compared to traditional fiat currencies, assets can be transferred faster on the bitcoin network. The system also has lower transaction fees, because it’s decentralized and there are no intermediaries, and it is cryptographically secure—the identities of the sender and the receiver are kept hidden, and it is impossible to counterfeit or hack the transactions. Plus, all the information is available on a public ledger, so anyone can view the transactions.

Bitcoin Advantages

What Is Blockchain?
As mentioned, blockchain is the underlying technology of bitcoin. Blockchain is a public distributed ledger in which transactions are recorded in chronological order. Any record or transaction added to the blockchain cannot be modified or altered, meaning transactions are safe from hacking. A block is the smallest unit of a blockchain, and it is a container that holds all the transaction details. A block has four fields, or primary attributes:

Previous hash: This attribute stores the value of the hash of the previous block, and that's how the blocks are linked to one another.
Data: This is the aggregated set of transactions included in this block—the set of transactions that were mined and validated and included in the block.
Nonce: In a “proof of work” consensus algorithm, which bitcoin uses, the nonce is a random value used to vary the output of the hash value. Every block is supposed to generate a hash value, and the nonce is the parameter that is used to generate that hash value. The proof of work is the process of transaction verification done in blockchain.
Hash: This is the value obtained by passing the previous hash value, the data and the nonce through the SHA-256 algorithm; it is the digital signature of the block.
SHA-256 is a cryptographic hash algorithm that produces a unique 256-bit alphanumeric hash value for any given input, and that is the unique feature of this cryptographic algorithm: Whatever input you give, it will always produce a 256-bit hash.

What is Blockchain

What Is Bitcoin Mining?
Bitcoin mining is the process of verifying bitcoin transactions and recording them in the public blockchain ledger. In blockchain, the transactions are verified by bitcoin users, so basically the transactions have to be verified by the participants of the network. Those who have the required hardware and computing power are called miners.

We will talk more about them later, but the important concept to understand here is that there is nothing like a centralized body—a regulatory body, a governing body, a bank—to make bitcoin transactions go through. Any user with mining hardware and Internet access can be a participant and contribute to the mining community.

The process is solved based on a difficult mathematical puzzle called proof of work. The proof of work is needed to validate the transaction and for the miner to earn a reward. All the miners are completing amongst themselves to mine a particular transaction; the miner who first solves the puzzle gets the reward. Miners are the network participants who have the necessary hardware and computing power to validate the transactions.

3 Concepts of Blockchain

To understand bitcoin mining, you have to first understand the three major concepts of blockchain.

- Public distributed ledger: A distributed ledger is a record of all transactions maintained in the blockchain network across the globe. In the network, the validation of transactions is done by bitcoin users.
- SHA-256: Blockchain prevents unauthorized access by using a hash function called SHA-256 to ensure that the blocks are kept secure. They are digitally signed. Their hash value, once generated, cannot be altered. SHA-256 takes an input string of any size and returns a fixed 256-bit output, and it is a one-way function—you cannot derive the reverse of the input reverse fully from the output (what you have generated).
- Proof of work: In blockchain mining, miners validate transactions by solving a difficult mathematical puzzle called proof of work. To do that, the primary objective of the miner is to determine the nonce value, and that nonce value is the mathematical puzzle that miners are required to solve to generate a hash that is less than the target defined by the network for a particular block.
Concept of Bitcoin Mining

Solving the Puzzle

In the bitcoin network, as mentioned, users called miners are trying to solve a mathematical puzzle. The puzzle is solved by varying a nonce that produces a hash value lower than a predefined condition, which is called a target. A miner verifies a transaction by solving the puzzle and adding the block to the blockchain when it’s confirmed and verified by other users. As of today, Bitcoin miners who solve a puzzle get a reward of 12.5 bitcoins.

Once a block is added to the blockchain, the bitcoins associated with the transactions can be spent and the transfer from one account to the other can be made.

To generate the hash, Bitcoin miners use the SHA-256 hashing algorithm and define the hash value. If it is less than the defined condition (the target), then the puzzle is deemed to be solved. If not, then they keep modifying the nonce value and repeat the SHA-256 hashing function to generate the hash value again, and they keep doing this process until they get the hash value that is less than the target.

Example: Transfer of 10 Bitcoins
Let’s say Beyonce wants to share 10 bitcoins with Jennifer. To do that, what would the steps be? First, transaction data is shared with bitcoin users from the memory pool. The transaction sits in an unmined pool of memory transactions. In a memory pool, unconfirmed transactions wait until they are verified and included in a new block. Bitcoin miners compete to validate the transaction using proof of work. The miner who solves the puzzle first shares the result across the other nodes. Once the block has been verified, the nonce has been generated, then the nodes will start granting their approval. If maximum nodes grant their approval, the block becomes valid and is added to the blockchain. The miner who has solved the puzzle will also receive a reward of 12.5 bitcoins, which as of today is around $98,000.

The 10 bitcoins for which the transaction was initiated now will be transferred from Beyonce to Jennifer.
