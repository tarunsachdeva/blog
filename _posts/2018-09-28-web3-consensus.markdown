---
layout: post
title:  "Web 3: Consensus"
date:   2018-09-28 12:00:00 -0500
categories: code
draft: false
---

The last few Future Friday's, I've focused on Web 3. I explored how the blockchain is paving the way for a [decentralized networks]({{ site.baseurl }}{% post_url 2018-09-16-decentralization-revisited %}), and how those networks can be developed and governed using [crypto tokens]({{ site.baseurl }}{% post_url 2018-09-21-web3-designing-networks-tokens %}) as incentives.

Today I want to cover some details of how data is transmitted and how people reach agreement within a decentralized world using Blockchains. 

In order for a decentralized world to work, there needs to be a few elements in place:

* The ability for one node in a network to reliably send messages to another without a central party - a reliable and trustworthy method of _peer-to-peer messaging_.
* The ability for multiple computers to agree on the validity of a transaction, a problem known as _consensus_. A transaction can be any blockchain-based transaction - it can be to record the transfer of digital assets like Bitcoin, but also for something like file transfers (as used in [IPFS](https://medium.com/@mycoralhealth/learn-to-securely-share-files-on-the-blockchain-with-ipfs-219ee47df54c)).

Both of these are solved by cryptography.

Peer to peer messaging is done using public-key cryptography and digital signatures. Public Key Cryptography is a cryptographic system that relies on a pair of keys, a  secret private key and an 'open' public key which is broadcasted out to the network. This system helps ensure the authenticity and integrity of a message by relying on advanced cryptographic techniques. ([source](https://www.blockchain-council.org/blockchain/how-does-blockchain-use-public-key-cryptography/))

Agreement on the validity of transaction is done using a _consensus algorithm_ agreed to by all members of the blockchain. This consensus algorithm is used to validate transactions on the chain without needing a central party. There are two forms of conensus ([source](https://mastanbtc.github.io/blockchainnotes/blockchaintypes/#what-is-consensus)):

* Permissionless, in which every node in the network participate in consensus procedure, e.g. Bitcoin Blockchain (Proof of Work)
* Permissioned, in which only Selected nodes (validators, e.g. Government or trusted nodes) participate in consensus procedure

Some of most common consensus algorithms being used by different blockchains today are Proof of Work (used by Bitcoin), and Proof of Stake.

* A Proof of Work (PoW), where a node on the network has to solve mathematically complex puzzles on the new block before approving the block to the ledger. After solving the puzzle, the solution is then forwarded to other miners and verified by them before being accepted to their respective copies of the ledger ([source](https://medium.com/@BangBitTech/what-is-consensus-algorithm-in-blockchain-different-types-of-consensus-models-12cce443fc77)). 
* Proof of Stake (PoS), in which a node on the network is selected to verify the transaction based on how much token ownership they have.

[This](https://medium.com/@BangBitTech/what-is-consensus-algorithm-in-blockchain-different-types-of-consensus-models-12cce443fc77) is a great article summarizing some of the most common consensus algorithms.

From [Web 3 Consensus Mechanisms](https://medium.com/imbrexblog/web-3-consensus-mechanisms-2dcfb7bfaadb) on the importance of consensus mechanisms.

> Consensus mechanisms are a integral to blockchain technology and other distributed systems. They are the basis on which participants of a given network with a range of varied self-interests, and even a mutual distrust for one another, can come to an agreement on the validity of data and transactions. **The consensus model implemented by a project, company or team is the heart of its security, communication, and sustainability**.