---
icon: binary-circle-check
---

# Clanker Token Ecosystem Benefits

## What are Clanker tokens?

**Clanker** is a smart contract framework and token deployment API for creating immutable, self-sustaining ERC-20 ecosystems. It enables creators to launch tokens with fixed liquidity, built-in fee routing, and no reliance on centralized developer controls. In short, it's a new kind of _Kickstarter_. Ozmium was created through the Causer project with the Clanker API with an initial market cap of 32 ETH to coincide with validator and yield related "layer 2 token-economics" the Play Service Ecosystem provides. The cost is a modest _0.2% of swap fees from the initial Uniswap liquidity pool_. The remaining 0.8% of the 1% swap fee is awarded to the Ozmium owner address and further funds development.

***

{% hint style="danger" %}
There is only **one official Ozmium token** as specified under the Project Token Details page. When interacting with Ozmium tokens, please verify the token address before interacting — clones with alternate addresses exist but may be flagged by tools such as **Blockaid**, **DEX screeners**, and **token safety overlays**.
{% endhint %}

***

### Permanent Liquidity Model

As a Clanker-based token, Ozmium uses a **permanent liquidity pool** model:

* Liquidity was fully deployed **automatically at launch** and **locked permanently.**
* The locked liquidity is a **1% fee pool** via **Uniswap v3** that anyone can swap over.

<table><thead><tr><th width="69.5555419921875">Fee</th><th>Recipient</th></tr></thead><tbody><tr><td>0.8%</td><td>Returned into the Ozmium token ecosystem.</td></tr><tr><td>0.2%</td><td>Sent to Clanker as a smart contract service fee.</td></tr></tbody></table>

### 100% Public Pool (Zero Vault)

Ozmium was launched with the decision to forego a developer vault, so a fair launch with a **100% public liquidity pool** was done, and **zero developer, team, or treasury allocations** were set aside meaning:

* No privileged insider supply.
* No reserved developer unlocks.
* No central control over price or liquidity.
* All project-owned tokens are self-bought.

As a result, Ozmium can **free-float in the open market**, used independently across **Base EVM dApps**, **"Oz" game clients**, or any ecosystem that supports ERC-20 interoperability.

***

## Uniswap Fee Breakdown

Every Ozmium transaction through the Clanker **Uniswap V3 LP** charges a **1% swap fee**, split as follows:

* **0.8%**: Sent to the Ozmium Ecosystem Treasury.
* **0.2%**: Protocol fee to Clanker (liquidity service provider.)

This 0.8% fee is applied differently based on trade direction:

| Trade Direction | Fee Taken As | Explanation                                  |
| --------------- | ------------ | -------------------------------------------- |
| **ETH → OZ**    | ETH          | Buys route ETH into the ecosystem reserve.   |
| **OZ → ETH**    | OZ           | Sells route OZ into the redistribution pool. |

***

### Project Ecosystem Treasury Strategy

All assets collected via the 0.8% ecosystem fee are deployed strategically:

#### ETH (from Buys)

* **Converted to cbETH or ETH** depending on periods of deep liquidity;
* Periodically swapped stablecoin yield (e.g., **4.1% APY via Coinbase**);
* Used to strategically **re-buy OZ for recycle** during market pullbacks.

#### OZ (from Sells)

* Held in a **non-custodial ecosystem reward pool** or vault;
* Used for rewards in **world loot tables, bounties, and narrative events;**
* Burned or airdropped to adjust circulation in response to network cycles.

***

### Token Flow Summary

```txt
User Buys OZ →
→ 0.8% in ETH collected.
→ ETH → cbETH (Low) or ETH → USDC (4.1% APY)
→ Yield Buys OZ → LP & Redistribution Events

User Sells OZ →
→ 0.8% in OZ collected.
→ Stored in reward treasury for LP & Redistribution Events.
```

{% hint style="warning" %}
### Liquidity Pool Risk Warning

Liquidity is fully deployed in a **Uniswap V3 single-sided LP**, which provides deep on-chain liquidity with immutable logic. However, users should understand:

* **Liquidity is locked**: The LP NFT is permanently locked using Clanker LP Locker. There is no withdrawal function by design.
* **Price is community-driven**: Token value is entirely market-based and may experience high volatility.
* **Impermanent Loss applies**: Swapping between ETH and OZ in the LP is subject to impermanent loss mechanics inherent in AMM models.
* **No guarantee of redemption**: Ozmium ($OZ) is a utility token with no promise of fiat or ETH redemption from the creators.
* **Contract risks**: Though audited by Clanker’s core stack, use of LPs and tokens in DeFi always involves smart contract risk.

Participation in the LP is fully voluntary and should only be done by those who understand the risks of Uniswap V3 and decentralized finance protocols.
{% endhint %}

This ensures a **self-sustaining economic loop** without reliance on token inflation, external incentives, or treasury grants. Learn more about Clanker and clank an ok banger by visiting: [**https://clanker.world**](https://clanker.world/)

***

###

```
```
