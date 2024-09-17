# Renting/Selling areas

## Rent Sign

#### Rent sign setup:

![Rent sign setup](https://camo.githubusercontent.com/0d36d4793bb0badecbcdfec06f80dde481c9d1d951650c153189ae6162f340dd/68747470733a2f2f696d6775722e636f6d2f616d35553753702e6a7067)

#### Explanation

Parameters surrounded by `[]` are optional. Parameters surrounded by `<>` are required.

* \[area]: This parameter is only needed if the sign is placed outside the area.
* `<interval>`: The tenant can extend their rental by `<interval>`. Time units: d (days), h (hours) and m (minutes). Default is `d`. Example: 15d = 15 days
* `<max>`: Is the max. duration of the rental.
* `<cost>`: Defines the cost per `<interval>`.

You can only set sub areas for rent. The default area can only be set for sale (= selling the whole land; more information below)

**Example:**

![](https://camo.githubusercontent.com/c10c1baa1f1dd2291111d04d1948f7aab739bb4ab42f0155715c9e7ed8a15ee3/68747470733a2f2f696d6775722e636f6d2f49583358776c4a2e6a7067)

#### When the Sign has been placed

* The rent sign is setup and players can now access it.
  * To rent this area, just click on the sign.
  * To add more time to your rental, just click again on the sign.
* Cancel rental
  * Tenants can use /lands rent cancel to cancel their rental while standing inside the area.
* Remove the rental
  * As the area owner you can either remove the sign or execute /lands rent remove while standing inside the area.

## Sell Sign

#### Sell sign setup

Sell signs can be placed in sub areas and in the default area (= selling the whole land)\
![Sell sign setup](https://camo.githubusercontent.com/11864a6ea4440b6f865f88f75178937db7b3cb053917891e4cf2a33daa753549/68747470733a2f2f696d6775722e636f6d2f517936387a4e682e6a7067)

#### Explanation

Parameters surrounded by `[]` are optional. Parameters surrounded by `<>` are required.

* \[area]: This parameter is only needed if the sign is placed outside the area.
* `<cost>`: Defines the total cost.

**Example**

![Sell sign result](https://camo.githubusercontent.com/a931aa6ff7f10862935584ece921e61b9dba16980d74daf66ac0ab52d2b02fa3/68747470733a2f2f696d6775722e636f6d2f3975527961794e2e6a7067)

#### When the Sign has been placed

[Click](https://github.com/Angeschossen/Lands/wiki/Rent-System/\_edit#when-the-sign-has-been-placed)

## Browse Listings

Use `/lands rent list` to view all areas and lands that can be rented or bought. There you can also filter and sort these offers.

\
\
