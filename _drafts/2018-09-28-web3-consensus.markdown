---
layout: post
title:  "Web 3: Trust"
date:   2018-09-28 12:00:00 -0500
categories: code
draft: true
---

* Trust and Consensus - I'll examine the concepts of how blockchains enable market consensus, how trust in decentralized networks is built, and how it can be applied more widely.

Governance - Consensus
Market Dynamics


NOTES

FROM:
https://medium.com/imbrexblog/web-3-consensus-mechanisms-2dcfb7bfaadb

To put it simply, a consensus mechanism is the means by which people reach agreement within a particular blockchain, specifically on the validity of transactions. 

A Proof of Work (PoW) is defined as a piece of data which is difficult (costly, time-consuming) to produce, yet easy for others to verify. 


Instead of confirming transactions using computational power, blockchains that use Proof of Stake (PoS) rely on users providing an economic stake in the network. 

A Directed Acyclic Graph (DAG) is a consensus mechanism that isn’t used by traditional blockchains such as Bitcoin and Ethereum. DAGs are used by distributed systems such as IOTA and Byteball where transactions are validated by paying-it-forward. In order to send a transaction, users must validate two transactions. This can allow for faster transaction speed when the network is under increased load. 

Holochain uses a Distributed Hash Table (DHT). A DHT is a distributed system with a lookup service that uses (key, value) pairs. These pairs are stored in the DHT, and any participating node can retrieve the data associated with the key. The maintenance and mapping of the keys are distributed amongst the nodes.

Proof of Location (PoL) is a new protocol enabling location verification. Instead of node operators receiving payouts for verifying transactions like in PoW, PoL payouts are location based, meaning participants are required to visit each site in a predefined order. 

Certain cryptocurrencies, including Bitcoin, that are operating under the proof of work consensus mechanism have deflationary currency supplies. 


Consensus mechanisms are a integral to blockchain technology and other distributed systems. They are the basis on which participants of a given network with a range of varied self-interests, and even a mutual distrust for one another, can come to an agreement on the validity of data and transactions. The consensus model implemented by a project, company or team is the heart of its security, communication, and sustainability.
