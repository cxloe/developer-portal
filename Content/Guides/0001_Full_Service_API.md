---
title: Full Service API 
---
The Full Service API is a JSONRPC API that works with command line tools and wallet services. It provides ledger syncing and validation, account management, and funds transfer and receiving. It serves the use cases of single user (and is the backing to the MobileCoin Desktop Wallet), while also serving high performance, multi-account, multi-subaddress needs (such as backing merchant services platforms). Please see the full API documentation at: [Full Service API](https://mobilecoin.gitbook.io/full-service-api/)

[![Docs](https://img.shields.io/badge/docs-latest-blue?style=for-the-badge)](https://mobilecoin.gitbook.io/full-service-api/) 
[![Chat](https://img.shields.io/discord/844353360348971068?style=for-the-badge)](http://mobilecoin.chat/) 
[![CircleCI](https://img.shields.io/circleci/build/gh/mobilecoinofficial/full-service?token=da755dc2814021ad04ee7b31a129b41e6c7161ac&style=for-the-badge)](https://circleci.com/gh/mobilecoinofficial/full-service/tree/master) 

The API supports:
* multiple accounts
* subaddresses (unique public addresses for incoming transactions, to assign per-user)
* balance-checking (totals, and per-user-incoming)
* transaction construction & submission
* transaction history store
* hot and cold operating modes

### Show Me the Code

* [Full-Service Node](https://github.com/mobilecoinofficial/full-service): Implementation of the Full-Service Node

