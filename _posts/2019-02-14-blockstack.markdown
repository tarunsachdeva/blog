---
layout: post
title:  "Some Notes on Blockstack"
comments: true
date:   2019-02-14 12:00:00 -0500
categories: technology
---

I've been interested in how the "Web 3.0" vision is evolving, and one of the companies that is leading the path is Blockstack - a platform for developing dApps (decentralized apps). 

Developing dApps requires a significant change in mental models for developers. But the core purpose of a development platform is the same - to help developers build, grow and monetize their apps.

Blockstack takes an interesting approach. All DApps are single page apps that interact with the `blockstack.js` library, which provide the core identity and storage services for a DApp. All the complexity for a Blockstack app is [moved to clients](https://en.wikipedia.org/wiki/End-to-end_principle) vs. on the blockchain itself through smart contracts. This makes sense since clients have the compute power, and the chain is only used for the core decentralization purposes. 

There are 3 principles that define what type of apps developers can build using Blockstack:
- Users own their _identity_, and have full control over how that is used. Blockstack provides the infrastructure to provide users that control. Decentralized identity is a fundamental part of every dApp.
- Users own their _data_, and can create apps on Blockstack using the [Gaia](https://github.com/blockstack/gaia) decentralized storage system
- Users have free choice of clients. Your identity and data can be easily transferred between dApps by default. You can build a dApp but if you are using Blockstack's Identity platform and decentralized data, it can technically be used by another app.

Some other notes:
- As a developer, I often want to bring decentralization into my apps in the form of **data** or **identity**. Blockstack provides an infrastructure for both of these, but it can be a bit hard to dig through. I wish their website was designed around helping developers around these principles, instead of being hidden in their [docs](https://docs.blockstack.org/develop/dapp_principles.html).
- [App Mining](https://app.co/mining) is a very interesting funding model. This pays developers based on contributions to the ecosystem, and rewards them on a regular basis based on app reviewers input ([more here](https://blog.blockstack.org/app-mining-game-theory-algorithm-design/)). While this isn't using a specific crypto token, it shares the spirit of financially supporting the developer of a dApp.