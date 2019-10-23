---
layout: post
title:  "Learning about Quantum Computing"
comments: true
date:   2019-10-23 12:00:00 -0500
categories: technology
draft: false
---

Yesterday, Google made an [announcement](https://ai.googleblog.com/2019/10/quantum-supremacy-using-programmable.html) about a breakthrough in Quantum computing. I don't know much about this topic but it was being discussed by a number of people I respect, so this is a self-serving learning post. 

Some learnings so far:

* Quantum is a hypothetical model of computation. Compared to classical computing in which _memory_ is represented in "bits" as 1's and 0's (a _bit_ is the smallest unit of data in a computer), quantum memory stores a *quantum state*. If you look at a wave form for classical computing, 1's and 0's are represented as on/off states: `-_-_-_-`. 
* Quantum states are like waveforms which in turn can be "added" (superimposed) to represent other quantum states.
* Quantum states are represented by [qubits](https://en.wikipedia.org/wiki/Qubit), basic unit of quantum information. There are two possible outcomes for the measurement of a qubit—usually taken to have the value "0" and "1", like a bit or binary digit. However, whereas the state of a bit can only be either 0 or 1, the general state of a qubit according to quantum mechanics can be a coherent superposition of both. Moreover, whereas a measurement of a classical bit would not disturb its state, a measurement of a qubit would destroy its coherence and irrevocably disturb the superposition state. It is possible to fully encode one bit in one qubit. 
* Quantum Supremacy is the concept of a crossover point, at which it becomes impossible to do something without representing and computing with quantum states. 
* If we compute using the rules of quantum mechanics, instead of binary logic, some intractable computational tasks become feasible. An important goal in the pursuit of a universal quantum computer is the determination of the smallest computational task that is prohibitively hard for today’s classical computers. 
* Google announced that it has created a 53-qubit processor. The computational task was to sample the output of a pseudo random quantum circuit and perform some operation on it that is really difficult for a classical computer to do. Each sample is represented by a bit-string (e.g. 1100011, 1010101, etc). 

I'll update this as my understanding of this topic increases.