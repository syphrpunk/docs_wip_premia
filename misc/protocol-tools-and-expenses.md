---
description: >-
  The protocol utilizes a number of non-free tools in order to provide the
  optimal user experience.
---

# Protocol Tools and Expenses

While it would be nice if the protocol ran itself free forever, there are a number of user-experience upgrades and protocol features that require continual expenses. These are the main tools used by the Premia protocol that require expenses to upkeep:

* Chainlink Price Feeds for accurate Pool pricing
* Chainlink Nodes for Volatility Surface Oracle
* Chainlink Keeper
  * Auto exercise of expired options
  * Convert protocol fees to PREMIA rewards
  * \[Future:] Enable take profit and stop loss orders
* The Graph on-chain indexing and open-source DB/API service to support the premia front-end interface and third party tools built on the Premia protocol
* Contract deployments

All of these must be maintained on a per-chain basis, causing expenses to scale per additional chain supported.
