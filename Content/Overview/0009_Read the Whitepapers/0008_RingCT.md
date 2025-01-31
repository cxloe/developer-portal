---
title: Ring Confidential Transactions
---

CryptoNote ledgers are significantly more secure than Bitcoin, but they still leave the amount of each transaction in plain sight. One potential solution was published in 2016 by Shen Noether, called Ring Confidential Transactions (RingCT). RingCT protects the amount exchanged in each transaction using cryptography. Rather than publish the value that is exchanged, RingCT transactions include a mathematical proof that the transaction is balanced, meaning that the recipient didn’t receive more money than the sender spent. This originally required a computationally intensive proof, but a more efficient algorithmic approach called Bulletproofs was introduced by Bünz et al. in 2017 that has greatly improved performance. It is now possible to use transactions with protected amounts without reducing the throughput of the payments network.

# [Download the Whitepaper](https://raw.githubusercontent.com/mobilecoinofficial/developer-portal/master/info/ringct.pdf)

[widget type='pdfViewer' pdf='//raw.githubusercontent.com/mobilecoinofficial/developer-portal/master/info/ringct.pdf']
