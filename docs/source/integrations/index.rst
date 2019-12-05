.. _integrations:

===================
Integrated Projects
===================

One of the ideas of the Hyperledger Consortium is to create solutions that could work together to provide the best blockchain experience possible. In Iroha we believe that integration of other awesome Hyperledger tools and solutions is a way to make Iroha better for your use-cases.
That is why we have worked on integrations with several projects and would like to tell you more about what Iroha can work with.

Hyperledger Ursa
================

`Hyperledger Ursa <https://wiki.hyperledger.org/display/ursa/Hyperledger+Ursa>`_ is a shared cryptographic library that would enable people (and projects) to avoid duplicating other cryptographic work and hopefully increase security in the process.
The library would be an opt-in repository for projects (and, potentially others) to place and use crypto.
Hyperledger Ursa consists of sub-projects, which are cohesive implementations of cryptographic code or interfaces to cryptographic code.

You can easily build Iroha with Ursa library by adding just `one flag during the build <../build/index.html#main-parameters>`_.
It will allow you to use crypto algorithms from Ursa library instead of standard Iroha cryptography.
With the development of new libraries in Ursa more and more options will be available to you!

Hyperledger Explorer
====================

`Hyperledger Explorer <https://wiki.hyperledger.org/display/explorer>`_ is a blockchain module and one of the Hyperledger projects hosted by The Linux Foundation.
Designed to create a user-friendly Web application, Hyperledger Explorer can view, invoke, deploy or query blocks, transactions and associated data, network information (name, status, list of nodes), chain codes and transaction families, as well as any other relevant information stored in the ledger.

`Here <https://github.com/turuslan/blockchain-explorer/blob/iroha-explorer-integration/iroha-explorer-integration.md>`_ you can learn how you can use Explorer with Iroha.

Hyperledger Burrow
==================

`Hyperledger Burrow <https://wiki.hyperledger.org/display/burrow>`_ provides a modular blockchain client with a permissioned smart contract interpreter partially developed to the specification of the Ethereum Virtual Machine (EVM).

We will soon prepare instructions on how to use Burrow integrated into Iroha.