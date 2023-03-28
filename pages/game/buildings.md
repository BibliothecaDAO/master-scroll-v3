import { Callout } from "nextra-theme-docs";

# Buildings

> In the role of a Realm Lord, one must meticulously weigh the advantages and disadvantages of each building to skillfully balance the statistics and cultivate a robust and flourishing Realm. This process involves not only finding equilibrium among the various structures but also recognizing the Realm's current needs and priorities. By focusing on specific buildings or upgrades that address these immediate requirements, Realm Lords can ensure the ongoing growth and prosperity of their domain while maintaining a strategic edge in their ever-evolving world.

![Buildings](/static/img/game/buildings/mj_hut.png)

## Spatial Areas

Buildings take up square space on your Realm so you must choose which ones to build.

You can calculate the spatial area of a Realm by:

> Regions \* Cities + 25 = buildable space

The max buildable squares formula is a constraint that determines the maximum amount of space that can be used for building at any given time in a Realm. If all available space has been built on, the ruler must either wait for buildings to decay or demolish existing structures in order to create more space for new buildings. It's important for the ruler to consider the long-term effects of demolishing buildings and the potential negative impact on the Realm's statistics before making this decision.

---

## Building Decay

Buildings in the game decay over time, this means you will have to continuously build your buildings. The current decay formulas can be found here.

## Building Types

### Military

Military buildings are an important aspect of a Lord's Realm as they unlock the ability to summon battalions for raiding other Realms and defending their own vault from raids. There are four types of military buildings in total, each of which unlocks different battalions for the Lord to use in battle.

These buildings are crucial for a Lord to be able to expand and protect their realm, and each type of building will have different benefits, drawbacks, and costs.

| Building                                                                       | Tier 1 Unit                                                                | Tier 2 Unit                                                                |
| ------------------------------------------------------------------------------ | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| **Archer House** ![Buildings](/static/img/game/buildings/mj_archery_range.png) | **Archer** ![Buildings](/static/img/game/battalions/mj_longbow.png)        | **Hunter** ![Buildings](/static/img/game/battalions/mj_hunter.png)         |
| **Mage Tower** ![Buildings](/static/img/game/buildings/mj_mage_tower.png)      | **Apprentice** ![Buildings](/static/img/game/battalions/mj_apprentice.png) | **Mage** ![Buildings](/static/img/game/battalions/mj_mage.png)             |
| **Castle** ![Buildings](/static/img/game/buildings/mj_castle.png)              | **Cavalry** ![Buildings](/static/img/game/battalions/mj_scout.png)         | **Knight** ![Buildings](/static/img/game/battalions/mj_knight.png)         |
| **Mage Tower** ![Buildings](/static/img/game/buildings/mj_barracks.png)        | **Soldier** ![Buildings](/static/img/game/battalions/mj_lightInfantry.png) | **Paladin** ![Buildings](/static/img/game/battalions/mj_heavyInfantry.png) |

### Agricultural

**Farms & Fishing Villages**

To keep a positive happiness level, a Realm Lord must ensure that there is enough food for the population at any given time. The higher the population and military units on a Realm, the more food required to maintain happiness and therefore increase resource output.

There are two agricultural buildings in the Eternum and they produce two different food:

| Building        | Image                                                           | Food Output |
| --------------- | --------------------------------------------------------------- | ----------- |
| Farm            | ![Buildings](/static/img/game/buildings/mj_farm.png)            | $WHEAT      |
| Fishing Village | ![Buildings](/static/img/game/buildings/mj_fishing_village.png) | $FISH       |

See the [Food](/docs/game/food) section for more information.

<Callout emoji="👾">$WHEAT and $FISH can be sold/purchased on the AMM</Callout>

## Storehouses

To distribute food to your population and troops, you must convert $FISH/$WHEAT into a storehouse.

Storehouses take up spatial areas on your Realm so you must be strategic about your buildings to ensure you always have enough room to feed your population, and therefore increase your resource output and troop's vitality.

Each 10,000 units of food in a storehouse takes up 2 sqm on your Realm, this means you cannot just hoard food on your Realm otherwise you will not be able to build anything else.
