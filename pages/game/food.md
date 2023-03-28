import { Callout } from "nextra-theme-docs";

# Food

> Food plays an essential role in the effective management of an empire. As the number of buildings and battalions within a Realm increases, so too does the demand for food. By providing their battalions with sufficient sustenance across their Realms, Realm Lords can boost their vitality and overall performance. To allocate food throughout a Realm, Realm Lords are required to convert it into storehouses. Food can be produced and cultivated by Realm Lords themselves, or alternatively, it can be purchased from the Automated Market Maker (AMM). This strategic distribution of food is crucial for maintaining a thriving and successful empire.

## What is Food

Food comes in two forms: $WHEAT and $FISH. You have two options to get food in Eternum; buy it from the market or farm it.

<Callout emoji="👾">
If you want to have a military to attack/defend (battalions) with a higher vitality, you will need to provide your Realm with food. Food is cheap and every realm can produce (or purchase) it, but you must manage it wisely or suffer the consequences.
</Callout>

## Rivers (Farms) & Harbors (Fishing Villages)

Farms are constrained to the number of rivers you have in your Realm, and fishing villages to your harbors. The higher number of farms/fishing villages you have built, the higher yield of $WHEAT/$FISH you’ll generate.
Each farm/fishing village generates 14,000 $WHEAT/$FISH per day.

![WIP of a game asset](/static/img/game/buildings/mj_fishing_village.png)

![WIP of a game asset](/static/img/game/buildings/mj_farm.png)

## Feeding your population and batallions

Storehouses are an important aspect of a Realm's economy as they allow a Lord to distribute food to their population and batallions. Once wheat or fish is harvested or purchased, it can be converted into storehouses to feed the population and batallions. Unlike farms and fishing villages, storehouses take up space in the Realm's spatial area, which means that building more storehouses will take up more space but will also feed the population and troops for longer periods of time. 

The rate at which storehouses deplete depends on the size of the population (armies + buildings), the greater the number of population, the greater the consumption rate. As a ruler, it is important to balance the number of storehouses with the size of the population and standing army in order to ensure a steady food supply for your realm.

Consumption rate is calculated by the following formula:

`Consumption rate = 1 food per second per Population`

### Building storehouses

The conversion rate is 10000:1, meaning that it takes 10000 units of food to create 1 square meter of storehouse. This conversion rate applies to both $WHEAT and $FISH. There is no limit to how many storehouses can be built, except for the available space on the Realm. 

The more storehouses that are built, the more food can be stored, and the longer the population and batallions can be fed.


{/* ![Food Production](/static/img/game/food-production.png) */}


{/* ![WIP of a game asset](/static/img/game/buildings/mj_storehouse.png) */}

## Trading excess food on the AMM

Once you harvest either $WHEAT/$FISH from your farms/Fishing villages, you have the option to trade any excess on the AMM for $LORDS.

In turn, this provides the opportunity for other Lords to purchase them instead of having to build farms/fishing villages and harvesting themselves. A Lord with low rivers/harbors with a penchant for raiding, or simply being time poor can benefit from this, while providing a $LORDS stream to productive farmers.

## Factors to consider

### Food consumption

Food consumption is calculated by your population. Buildings and battalions count towards your population, the more you have, the faster your food is depleted.

If your Realm runs out of food, you will be permanently capped at 250 resource production and your armies will be at 50% health when they fight, drastically reducing your chances of success.
