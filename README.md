# Plutus

This repository holds the code for in-application money management for Blockstack.  It will not hold code, but will be the community's point of contact for issues about the design and implementation of this subsystem.  The code itself will be merged to [Blockstack Core](https://github.com/blockstack/blockstack-core).

We expect to have this working as a PoC by the end of summer 2017.

# Design Notes

Blockstack is built on top of one or more blockchains (via Chronos).  Registering Blockstack names requires spending the on-chain token.  Moreover, Blockstack applications will need a way to bill users for services rendered, preferably using these blockchain tokens.  This means that Blockstack apps need a way to send, receive, bill, and spend tokens on behalf of their users.

# Deliverables

* An API endpoint for sending tokens to the owner of a Blockstack name
* An API endpoint for tracking payments from a user
* An API endpoint for buying more tokens

# Point of Contact

* Jude Nelson (@jude on blockstack.slack.com)

# How can I help?

Glad you asked!

* Post questions as Github issues
* PRs are welcome :)
