---
layout: post
title: blockring the new internet
base: ../../../
---
![drit-logo]({{page.base}}img/drit-brand.svg)
## The blockchain is more than the internet of value

Blockchains have been around for a long time.
In fact they have existed since
the invention of one-way hashes and asymetric signatures.

We have been linking electronic documents since the existance
of version control systems. The blockchain is the old internet.
It might even have existed before internet protocols [KWIC 1958][1].

Every software developed with git is using a blockchain to reach an agreement on
the right version to use. All timestamping services are a blockchain.

The blockchain is more than a ledger for accounting values.
The financial use of blockchain is one "natural" use case of electronic ledgers.
All electronic exchanges, archived documents and human interactions
can be accounted for over a blockchain enabling knowledge sharing, process optimization
and collective decision making at a global scale. These are the benefits of the blockchain.
So we might see an evolution in which we tokenize everything to track and optimize our
resources. This will become the new internet.

A blockchain consists of two elements :

1. A set of documents which are cryptographically linked
   (any document which has a reference to a previous one is a block of a blockchain);
2. A consensus mechanism to point to the HEAD of the chain.

What classical "modern" blockchains bring is the "anonymity" which allows anyone
to update the ledger without being authenticated.
As a consequence, these trust-less blockchains are subject to abuse.
Therefore they require a [hashcash][2] algorithm to mitigate spam and fraud.
The proof-of-work based consensus prevents double spending of cryptocurrencies. 

This approach for securing a blockchain is very energy consumptive and hampers
the internet adoption of blockchains.
The blockchain will not be the new internet if the proof-of-work consensus remains the same.
In order to stay, Bitcoin and Etherium will have to undergo [hardforks][3].
There are other consensus mechanisms that are friendlier
and are not using any proof-of-work nor proof-of-stake. 
We will see more and more of these architectures in a near future.


Permissionned blockchains provide authentication and are not prone to the same abuse
which make the consensus easier to address.
For instance the use of conflict free replication on [merkleDAG][5] trees doesn't
requires lots of energy to converge; we call them blocktrees.

![blockring]({{page.base}}img/blockringinfo.png)

Moreover, an "open-ended" chain or tree is by construction mutable.
It continiously grows which makes it hard to track changes and limits it usability.

It takes 10-minutes to generate a block on the Bitcoin blockchain.
One has to wait for several confirmations to "validate" transactions.
For example, 6 confirmations require an hour compared for a few seconds for a credit-card transaction.
This lowers user acceptance of blockchain technology.

This is where Blockring solves the problem.
It closes the chains making them immutable and self-contained.
There is no need for extra delay to secure the closed chain.
We call these closed permissioned chains: Blockrings.

[1]: https://archive.today/2019.06.25-085821/https://spectrum.ieee.org/tech-history/silicon-revolution/hans-peter-luhn-and-the-birth-of-the-hashing-algorithm
[2]: https://www.hashcash.org/papers/announce.txt
[3]: https://duckduckgo.com/?q=hardfork
[4]: https://www.blockring™.ml
[5]: https://duckduckgo.com/?q=merkle+DAG+CxRDT
