---
description: Future Directions for the xDai Stable Chain
---

# Roadmap

## Fiat to xDai Onramp

**Target:** Q4 2019  
**Status:** Carbon implementation complete, additional implementations ongoing.

{% hint style="success" %}
The [Carbon on-ramp](../for-users/buying-xdai-with-carbon/) for xDai is now functional \(functionality is dependent on geo-location\).
{% endhint %}

At the moment, to get xDai, most users have to get Dai first and relay it to xDai via xDai Bridge. The process is complicated and time-consuming due to congestions on the Ethereum networks and the probabilistic nature of Proof of Work consensus. Relayers of the xDai bridge are waiting for eight blocks on Ethereum before they relay Dai to xDai.

The xDai team is working with payment processing companies to enable Fiat to xDai onramp. To facilitate the integration of xDai fiat onramp into wallets, the team started "xDai Adoption Fund" [https://www.xdaichain.com/for-developers/grants\#xdai-adoption-fund](https://www.xdaichain.com/for-developers/grants#xdai-adoption-fund)

## **Multi-Collateral Dai &lt;-&gt; xDai Bridge**

**Target Date:** Q4 2019  
**Status**: Done. Summary: [https://forum.poa.network/t/migration-of-the-xdai-tokenbridge-completed/3212](https://forum.poa.network/t/migration-of-the-xdai-tokenbridge-completed/3212)

{% hint style="success" %}
xDai bridge is upgraded to support both Dai and Sai.

Bridge balance migrated from Sai to Dai. Both Dai and Sai can be deposited on the Ethereum side. Sai to Dai converted automatically.
{% endhint %}

Once the Dai protocol implementation is upgraded to MCD \(Multi-Collateral Dai\), the xDai bridge will also be upgraded to use MCD Dai.

## Consensus Upgrade

**Target Date:** Q1 2020

xDai currently uses known organizations in the ecosystem as chain validators. These organizations subsidize their own nodes, and this is unsustainable in the long term. To increase decentralization, and offer the broader community the chance to participate in consensus, we will upgrade to the POSDAO consensus model.

For more information on this transition, see the [STAKE and staking page](stake-and-staking.md).

## **Privacy Preserving Transactions**

**Target Date:** Q3 2020

Implementation of additional zero-knowledge protocols and private transactions into xDai.

Since xDai is a stable token, the primary use of the chain is peer-to-peer payments. Just as with cash, privacy should be an option when exchanging money or paying vendors for services. It doesn’t matter if you are sending money to a relative or your local butcher. You should have the freedom to choose that any transaction remain anonymous.

We have invested in several [different approaches ](https://forum.poa.network/t/introducing-the-poa-zero-knowledge-fund/2698)to implement different ZK protocols into xDai based applications and wallets.

## Synthetic Assets on xDai based on UMA protocol

**Taget Date**: Q2 2020

> UMA is a decentralized financial contracts platform built to enable Universal Market Access. Use UMA’s self-enforcing contract design patterns and provably honest oracle mechanism to create your own financial products using standards like ERC20

xDai will leverage UMA protocol to create derivatives on fiat currencies and enable them in supporting wallets.

## L2 scalability for token transfers on xDai

**Target Date**: Q3 2020

A scalability solution based on zero-knowledge protocol \(Rollup\) will be deployed on xDai. This will enable scaling of transfers \(up to 1000x\) for native token and synthetic tokens on top of xDai.

## xDai NG \(New Generation\) POS Chain

**Target Date**: Q3 2020

A chain created specifically to leverage [POSDAO](../for-validators/posdao-whitepaper.md), HoneyBadger BFT and Multi-Collateral DAI. This network will be designed from the ground up to use [STAKE](../for-validators/staking-protocol/get-stake-tokens.md) tokens and HBBFT consensus.

