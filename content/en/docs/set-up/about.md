---
title: "About Lotus"
description: "Lotus is a Filecoin implementation written by Protocol Labs, the creators of IPFS, libp2p, and Filecoin."
lead: "Lotus is a Filecoin implementation written by Protocol Labs, the creators of IPFS, libp2p, and Filecoin."
draft: false
menu:
    docs:
        parent: "node-set-up"
weight: 10
toc: true
---

It is written in [Go](https://golang.org) and it is actually a suite of command-line applications:

- Lotus Node (`lotus`): a Filecoin Node: validates network transactions, manages a FIL wallet, can perform storage and retrieval deals.
- Lotus Miner (`lotus-miner`): a Filecoin miner. See the the respective [Lotus Miner](../../mine/lotus/README.md) section in the [Mine](../../mine/README.md) documentation.
- Lotus Worker (`lotus-worker`): a worker that assists miners to perform mining-related tasks. See its respective [guide](../../mine/lotus/seal-workers.md) for more information.

The installation instructions are common to all three, but this section just focuses on getting started with the **Lotus Node**: installing, launching, syncing the chain and managing a Lotus wallet. Documentation on how to make storage deals using Lotus is available in the [store](../../store/lotus/README.md) section. Additional documentation is also available for [miners](../../mine/lotus/README.md) and [developers](../../build/lotus/README.md)!

{{< alert icon="warning" >}}
Lotus is a command line application that **works on Linux and MacOS only**, and needs to be **built from source**. Users should be familiar with how command-line applications work.
{{< /alert >}}

## Getting started with Lotus

These are the main guides to swiftly get started with Lotus:

- [Install and launch a Lotus node]({{< relref "install" >}})
- [Create a wallet and send or receive FIL to your address]({{< relref "manage-fil" >}})
- [Switch between different networks]({{< relref "switch-networks" >}})
- [Learn about the Lotus configuration]({{< relref "configuration" >}})

Please check the side menu for additional guides!
