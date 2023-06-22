# Passive Staking and Limited Active Parties for Adventurers

## Summary

Many players find it difficult to actively manage a medium to large collection of adventurers while doing quests. Additionally, future game progression would benefit from a limited number of adventurers that players can actively play with.

Therefore, we propose implementing a division between passive collection staking and active adventurer parties. This should be done before introducing the Inn Reputation System so that we can consider these changes while designing the system.

## Challenge & Opportunities

Currently, the game is in an awkward position where it doesn't provide the perfect staking experience or the ideal gaming experience. There are no limits to the number of adventurers you can send on quests, and there are infinite quests available, which makes staking tedious and hampers future game progression systems.

Many players have a substantial number of adventurers, making it difficult and tiresome to constantly send them on quests. They want to continue earning Dragon Silver with their adventurers, but they also desire a more manageable and enjoyable gameplay experience. They want their choices of actively playing with certain adventurers to feel meaningful and special.

Furthermore, game progression would benefit from limiting the number of active adventurers, furniture, and pets players can use. This limitation can be increased in the future through different activities, such as acquiring more tables and beds, unlocking larger Inns, or raising the leadership stat of specific adventurers.

Lastly, this aligns with our ultimate goal of dividing the game world into the Eternal Realms and the Mortal Realms.

## Proposed Solution

We suggest allowing players to passively earn Dragon Silver by holding onto their adventurers. The proposed function and algorithm are outlined below.

To implement this, we will introduce a new interface called the Party Management App. Through this app, players can choose which adventurers they want to actively play with, which ones will passively earn Dragon Silver, and the amount of Dragon Silver each "benched" adventurer will generate.

The amount of Dragon Silver earned through active questing will be significantly higher than the amount earned through passive staking. This will create incentives for players to progress through the game.

Initially, players will be able to actively use up to 7 adventurers. In a future update, we plan to introduce a system to increase this number. For example, it could be based on the number of tables in a player's tavern or by improving their tavern's reputation.

## Passive Staking Earned DS

