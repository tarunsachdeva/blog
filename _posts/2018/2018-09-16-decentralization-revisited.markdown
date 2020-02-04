---
layout: post
title:  "Decentralization, Revisited"
comments: true
date:   2018-09-16 12:00:00 -0500
categories: technology
draft: false
---

**NOTE**: A few days, ago, I [wrote]({{ site.baseurl }}{% post_url 2018-09-14-web3-decentralization %}) about decentralization as the foundational concept behind [Web 3]({{ site.baseurl }}{% post_url 2018-09-07-future-fridays-web3 %}). In this post, I wanted to dig into this a bit further - specifically focusing on why the power shift between application developers to protocol developers is so important. Again, there are a [number](http://www.usv.com/blog/fat-protocols) of [amazing](https://continuations.com/post/105272022635/bitcoin-clarifying-the-foundational-innovation-of) [articles](https://continuations.com/post/148098927445/crypto-tokens-and-the-coming-age-of-protocol) that helped me develop my understanding of this topic.

The Internet we know today exists because of two fundamental aspects of software: **protocols** and **applications**.

**Protocols** are the defined _rules_ of how information is transmitted between computers on the internet. Some of the most important protocols for the today's internet are [TCP/IP](https://en.wikipedia.org/wiki/Internet_protocol_suite), [HTTP](https://en.wikipedia.org/wiki/HTTP), [SMTP](https://en.wikipedia.org/wiki/SMTP), and [others](https://en.wikibooks.org/wiki/Network_Plus_Certification/Technologies/Common_Protocols). 

**Applications** are what end users interact with. Applications provide additional higher order functions - like presentation, logic, and memory. These higher order functions necessary to create any useful product or service for end users: the _presentation layer_ provides interfaces to interact with, the _memory layer_ (or _data layer_) provides the ability to store data, and the _logic layer_ provides additional functional capability. Applications _use_ open protocols for communication. For example, Gmail uses the SMTP protocol. 

Put together, applications and protocols are the building blocks for today's internet applications. This structure is reflected in popular development frameworks like [MVC](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller).

Applications today have **all** the control over the presentation, logic and data of their products and services. This has allowed for incredible innovations, convenience to end users, and ultimately a lot of value created. Application developers today represent some of the most valuable companies in the world. Most importantly, there is an implicit trust built into this architecture - that application developers will always act in the best interest of it's users.

We have seen this is not always the case. Application developers can abuse, neglect or be irresponsible with this level of control, and it has major negative downstream impact. The popularity of mobile and internet services makes this level of control a social and political issue around the world. We are seeing this play out in various ways.

From the beginning of the Internet until recently, there really was no **technical solution** to the problem of applications having full control of layers of internet products. Put another way, there was no way to bake in **trust** into applications without a central party. Providing that same level of service meant control over presentation, logic and data.

In 2008, this changed with the arrival of Bitcoin and it's underlying invention - the Blockchain. 

In technical terms, the Blockchain is a database distributed across multiple computers in the form of a ledger, that uses cryptographic techniques to ensure data cannot be tampered with once "written to the chain". While distributed databases were possible before the blockchain, there was no way to ensure all computers had the same data (without a 'central' authority) without some novel [cryptographic functions](https://www.coindesk.com/information/how-does-blockchain-technology-work/) that made this possible. As Ben Horowitz put it, "you don't have to trust any computers - you just have to trust the math". 

With this technology, multiple computers can come to agreement on the state of an application's data and logic without a central party. This is **a framework for _data_ and _logic_ to live outside the application layer, and into the protocol layer itself**.

Without knowing how it all works, just this simple fact is important - **that we can build useful services without giving up control of the data and logic to a single application developer**. This can be an existential threat for some of the most valuable companies in the world which are built on the existing structure of value in the application layer.

Decentralization is the process of making this change - of products and services moving into the shared protocol layer, with fundamentally different incentives and power structures than what exists today. 