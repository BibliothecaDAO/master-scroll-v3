import { Callout } from "nextra-theme-docs";

# Overview

> "Empires rise and fall in the quest for control of Resources and Ancient Relics within an eternal world. Maintain and defend your empire or it will fall into disarray and be consumed by enemies."

---

<Callout emoji="👾">
  All statistics and figures in this document are subject to change slightly as
  the alpha and beta versions of the game are released and balanced.
</Callout>
<Callout emoji="👾">
  You require a Realm in order to participate within this game
  ([OpenSea](https://opensea.io/collection/lootrealms)/[LooksRare](https://looksrare.org/collections/0x7AFe30cB3E53dba6801aa0EA647A0EcEA7cBe18d)).
  The first expansion of this game will be centered around the Adventurers NFT
  which will be free to play.
</Callout>

---

# On-chain & eternal strategy game

Eternum is a strategy game that is built on StarkNet. It is a game of management and conquest, where players must build and defend their Realm to thrive. The game is governed by a set of rules that are enforced by the game's smart contracts.

Once the production version of the game is live, it will exist for the duration of Ethereum. The game is run on StarkNet, but all state changes will still be recorded on the Ethereum blockchain, which was one of the primary factors in the decision to use an L2 solution rather than a sidechain. This ensures that the game's data and state will be stored on a decentralized, tamper-proof and immutable ledger for the longest possible period, providing players with a fair and transparent gaming experience.

![Eternum](static/img/screenshots/eternum-atlas.png)

### Digital physics

Eternum is an on-chain physics engine that has its ruleset permanently recorded on the blockchain and can only be altered through community voting. It serves as a foundation for developers to build upon, however, unlike our reality it is not pre-determined. The game's physics are governed by a set of rules that are enforced by the game's smart contracts. These rules are not fixed and can be changed by the community through voting.

#### Cartisean coordinates

Realms and other entities in the game are represented by a set of coordinates on a 2D plane. This the constraint of the world. All entities must travel from [x,y] to [x,y] to reach their destination.

#### Time

Time governs the pace of the game and is all based of the day cycle, which at inception will be 24hrs. It affects how quickly players can travel and how long it takes to build structures. The element of time is not fixed and can be affected by the community. The community can vote to speed up or slow down the passage of time, which will affect the rate at which players can travel and build structures.

#### Tick cycle

The game is governed by a tick cycle. Every 12hrs a tick happens in the game. Behinds the scenese every action you take on your Realm will call a function which will update the state of your Realm if you are outside of the last tick.

#### Entropy

Entropy is a measure of the randomness of the game. It is used to determine the outcome of certain events, such as the influence the outcome of battles. The community can vote to increase or decrease the entropy of the game, which will affect the outcome of certain events.

#### Labor costs

Everything in our reality has a energy cost, Eternum is no different. The fundamental building blocks of Eternum are it's resources. To generate these resources players must purchase Labor, which itself costs resources. So we can be certain if we see 250 $WOOD in the economy some resources have spent. The cost of Labor will begin at 42% of the resource's relative rarity value.

### Liquid markets

In the game, resources and other assets are represented as user-owned, tradable tokens. These tokens can be used to create buildings, troops and acquire resources from other players through pillaging, all in pursuit of greatness. These tokens can be traded on the open market, creating a dynamic economy within the game.

### Player agency

The game requires players to make strategic decisions as every action has a reaction, such as balancing resources and protecting the vault to successfully rule the Realm. This complexity adds depth to the game and requires players to make difficult choices.

## Open source and permissionless

Eternum is an open source project and is available on [GitHub](https://github.com/BibliothecaDAO/realms-contracts). The contracts are written in Cairo and anyone is able to contribute.