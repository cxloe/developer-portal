---
title: Byzantine Agreement
---
MobileCoin users must agree on the content of the blockchain for it to be useful as a record of accounts. Bad actors
will have a financial motive to misrepresent the ledger to enable fraud and counterfeiting. In distributed computing,
the challenge of reaching agreement in a group that cannot exclude malicious agents from participating is called the
Byzantine Agreement Problem. All cryptocurrency payment networks must include code that solves the Byzantine Agreement
Problem.

The MobileCoin Consensus Protocol solves the Byzantine Agreement Problem by requiring each user to specify a set of
peers that they trust, called a quorum. Quorums are based on the real-life trust relationships between individuals,
businesses, and other organizations that compose the MobileCoin Network. There is no central authority in the MobileCoin
Network. Users accept statements about the blockchain ledger when their quorum convinces them that these statements are
true. While the algorithmic design of MCP is based on the Stellar Consensus Protocol, the MobileCoin Network is not
interoperable with the Stellar payment network.

The MobileCoin Consensus Protocol avoids the environmentally-damaging mathematical “work” required by Proof-of-Work
(PoW) consensus protocols like Bitcoin and realizes a much higher transaction rate than the Bitcoin consensus protocol.
In contrast to Proof-of-Stake (PoS) consensus protocols, practical control of governance in MCP is ceded to the users
who are trusted the most by the extended MobileCoin community, rather than to the wealthiest users who control the
largest financial stakes.

MCP ensures that all operators agree on the sequence of valid payments that are completed. New transactions are grouped
in blocks and published approximately once every five seconds to the MobileCoin Ledger.

### Show Me the Code

* [Consensus Service](https://github.com/mobilecoinfoundation/mobilecoin/tree/master/consensus/service): The implementation of the MobileCoin Consensus Protocol Service
* [SCP](https://github.com/mobilecoinfoundation/mobilecoin/tree/master/consensus/scp): MobileCoin's implementation of the Stellar Consensus Protocol
