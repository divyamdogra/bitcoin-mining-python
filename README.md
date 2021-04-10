# bitcoin-mining-python

<h3>What is Bitcoin Mining? </h3>

Bitcoin mining is the process of verifying bitcoin transactions and recording them in the public blockchain ledger. In blockchain, the transactions are verified by bitcoin users, so basically the transactions have to be verified by the participants of the network. Those who have the required hardware and computing power are called miners.

We will talk more about them later, but the important concept to understand here is that there is nothing like a centralized body—a regulatory body, a governing body, a bank—to make bitcoin transactions go through. Any user with mining hardware and Internet access can be a participant and contribute to the mining community.

The process is solved based on a difficult mathematical puzzle called proof of work. The proof of work is needed to validate the transaction and for the miner to earn a reward. All the miners are completing amongst themselves to mine a particular transaction; the miner who first solves the puzzle gets the reward. Miners are the network participants who have the necessary hardware and computing power to validate the transactions.

<h3> 3 Concepts of Blockchain   </h3>

To understand bitcoin mining, you have to first understand the three major concepts of blockchain.

Public distributed ledger: A distributed ledger is a record of all transactions maintained in the blockchain network across the globe. In the network, the validation of transactions is done by bitcoin users.
SHA-256: Blockchain prevents unauthorized access by using a hash function called SHA-256 to ensure that the blocks are kept secure. They are digitally signed. Their hash value, once generated, cannot be altered. SHA-256 takes an input string of any size and returns a fixed 256-bit output, and it is a one-way function—you cannot derive the reverse of the input reverse fully from the output (what you have generated).
Proof of work: In blockchain mining, miners validate transactions by solving a difficult mathematical puzzle called proof of work. To do that, the primary objective of the miner is to determine the nonce value, and that nonce value is the mathematical puzzle that miners are required to solve to generate a hash that is less than the target defined by the network for a particular block.

<h3> Solving the Puzzle </h3>

In the bitcoin network, as mentioned, users called miners are trying to solve a mathematical puzzle. The puzzle is solved by varying a nonce that produces a hash value lower than a predefined condition, which is called a target. A miner verifies a transaction by solving the puzzle and adding the block to the blockchain when it’s confirmed and verified by other users. As of today, Bitcoin miners who solve a puzzle get a reward of 12.5 bitcoins.

Once a block is added to the blockchain, the bitcoins associated with the transactions can be spent and the transfer from one account to the other can be made.

To generate the hash, Bitcoin miners use the SHA-256 hashing algorithm and define the hash value. If it is less than the defined condition (the target), then the puzzle is deemed to be solved. If not, then they keep modifying the nonce value and repeat the SHA-256 hashing function to generate the hash value again, and they keep doing this process until they get the hash value that is less than the target.

<h3>Example: Transfer of 10 Bitcoins</h3>
Let’s say Beyonce wants to share 10 bitcoins with Jennifer. To do that, what would the steps be? First, transaction data is shared with bitcoin users from the memory pool. The transaction sits in an unmined pool of memory transactions. In a memory pool, unconfirmed transactions wait until they are verified and included in a new block. Bitcoin miners compete to validate the transaction using proof of work. The miner who solves the puzzle first shares the result across the other nodes. Once the block has been verified, the nonce has been generated, then the nodes will start granting their approval. If maximum nodes grant their approval, the block becomes valid and is added to the blockchain. The miner who has solved the puzzle will also receive a reward of 12.5 bitcoins, which as of today is around $98,000.

The 10 bitcoins for which the transaction was initiated now will be transferred from Beyonce to Jennifer.



![image](https://user-images.githubusercontent.com/48207530/114278025-686b0180-9a4b-11eb-82a7-b80be883a40f.png)
![image](https://user-images.githubusercontent.com/48207530/114278009-5ab57c00-9a4b-11eb-8fa3-1e3991343dcf.png)

