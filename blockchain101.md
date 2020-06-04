# BLOCKCHAIN 101


Just a chain of blocks. **No, it's much more** let's dive into blockchain to know about this technology.

## What is Blockchain?

>**Blockchain is a distributed ledger based technology which uses consensus based decisions to achieve trust in a peer-2-peer network among unknown peers.** 

*Didn't get all of that at once? You will get that soon.*

---

#### 1. Blocks in a blockchain
Blocks in blockchain hold batches of valid transactions that are hashed and encoded into a Merkle tree data structure. Each block includes the cryptographic hash of the prior block in the blockchain, linking the two. 

![Structure of blocks](capture1.png)
#### 2. Chaining of Blocks
The linked blocks form a chain. This iterative process confirms the integrity of the previous block, all the way back to the original genesis block. Each block also has a timestamp and a nonce associated with it. Therefore all the data inside blockchain becomes immutable.

#### 3. Technologies involved in Blockchain
Blockchain involves three main technologies:

* Private Key Cryptography
	* Asymmetric Encryption : Generates a pair of key for an account namely a public key and a private key. Encrypt with public key and decrypt with private key and vice versa.

* Peer-2-Peer Network
	* Distributed ledger: No cenralized database everybody has a copy of all the data.
	* Majority: To make any changes/additions majority of votes is required.
* Blockchain Protocol
	* Hashing: Converting any type/form of data to a fixed length string[hash] depending on its content.


*Ethereum is same as Blockchain? Most people are still confused.* 

#### 4. Ethereum
Ethereum is an open software platform based on Blockchain technology that enables developers to build and deploy decentralized applications. Ethereum’s coding language solidity helps write smart contracts. Its native currency is eth. It was founded by Vitalik Buterin. 

*Contracts + Blockchain => Smart Contracts*

#### 5. Smart Contracts
A smart contract is a computer protocol intended to digitally facilitate, verify, or enforce the negotiation or performance of a contract. Smart contracts allow the performance of credible transactions without third parties. These transactions are trackable and irreversible.

![Smart Contract Execution](capture3.png)

*32 bit or 64 bit? Step into the Future with __256 bit__ machines.*

#### 6. Ethereum Virtual Machine
An Ethereum virtual machine provides a run anywhere obstruction layer for the smart contracts.EVMs are 256 bit machines having extensive power for performing mining. A smart contract written in HLL is translated into EVM bytecode and then deployed on EVM. Every node will host the smart contract codes on the EVM.

*~~Application~~ => Dapplication*

#### 7.Dapplication
A decentralized application is a computer application that runs on a distributed computing system. They have distributed ledger[DLT] based technology. It has a web-front and blockchain back-end and the smart contract connecting both. 

*What's your favourite coding language?*

#### 8.Solidity
Solidity is a contract oriented language. It is designed to target the Ethereum Virtual Machine. It is statically typed language, supporting inheritance, libraries and complex userdefined types. 

---

*So that was the __Beauty of Blockchain__ for you !!*

---
___

#### Swapnil Kole  [@foody_kole] 

Blockchain Developer at Superworld

Blockchain Instructor at JP Courses

Publication: COVID-19 Database on Consortium Blockchain

Project: Certification on Blockchain
