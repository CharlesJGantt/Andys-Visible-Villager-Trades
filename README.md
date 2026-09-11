<p align="center"><img src="Andys-Visible-Villager-Trades-Hero-16x9-FINAL.png" alt="Andy's Visible Villager Trades — Andy beside a librarian villager and visible trade items"></p>

# Andy's Visible Villager Trades

See generated future villager offers while Minecraft keeps them locked, then inspect supported villager details with an empty-hand crouch-interact.

Current version: **0.2.0** for Minecraft Bedrock **26.30+**.

[Download the combined `.mcaddon`](Andys_Visible_Villager_Trades_0.2.0.mcaddon)

SHA-256: <!-- SHA256 -->`df53eef3f4222a46cfe46db7167cbb21fa398fc9d4e0850898f91fcf3b027c08`<!-- /SHA256 -->

## Features

- Future Novice-to-Master offers shown in the familiar native trade screen
- Native prices, demand, discounts, stock, XP, quantities, locks, and item tooltips preserved
- Locked offers remain read-only until normal villager progression unlocks them
- Empty-hand crouch-interact details for villagers, zombie villagers, and Wandering Traders
- Read-only carried inventory plus live type, profession when available, age, health, curing animation, and position
- Bounded, clearly qualified records of interactions and observed events after installation
- Operator menu by interacting with a block or entity using a stick renamed `AdminTradeControll`
- Cheats-free Bedrock Dedicated Server console commands
- Standard graphics and Vibrant Visuals support

## See future offers

<p align="center"><img src="images/trades-visible-1.png" width="700" alt="A novice librarian trade screen showing locked Apprentice and Journeyman offers"></p>

The preview uses Minecraft's generated offer data and leaves future rows locked. Scroll normally to inspect the rest of the villager's generated progression.

<p align="center"><img src="images/trades-visible-2.png" width="700" alt="Later librarian tiers through Master displayed while still locked"></p>

## Inspect villagers

<p align="center"><img src="images/villager-details-1.png" width="700" alt="Villager Details showing type, profession, age, health, position, and tracking date"></p>

<p align="center"><img src="images/villager-details-2.png" width="700" alt="Villager Details menu with carried inventory, interactions, observed events, and refresh controls"></p>

<p align="center"><img src="images/villager-carried-inventory.png" width="700" alt="Read-only villager carried inventory showing occupied slots and item counts"></p>

## Recorded activity

The add-on records normal interactions separately from confirmed purchases and clearly explains the limit in the panel.

<p align="center"><img src="images/villager-player-interactions.png" width="700" alt="Player interaction history explaining that interactions are not confirmed purchases"></p>

Observed events are also limited to what happened while the entity was tracked.

<p align="center"><img src="images/observed-events.png" width="700" alt="Observed-events screen explaining the retained event history and its limits"></p>

## World controls and graphics

World operators can manage every inspector category with `AdminTradeControll` or the documented dedicated-server commands. The Resource Pack declares PBR support for Vibrant Visuals.

## Install

1. Download and open the `.mcaddon` with Minecraft.
2. Edit the target world and activate the add-on. Confirm its linked Behavior and Resource Packs are both active.
3. Leave experiments and cheats off.
4. Open a villager's trade screen to browse future tiers.
5. Empty your main hand, crouch, and interact with a supported trader to open Villager Details.

World settings affect the inspector and its recording categories. Future-offer visibility remains active while the Resource Pack is active. The stable API cannot confirm completed transactions or recover earlier entity history, so interactions are labeled “purchase unconfirmed” and unknown history is left unknown.

For setup, commands, limits, and troubleshooting, see the [Player Guide Wiki](https://github.com/CharlesJGantt/Andys-Visible-Villager-Trades/wiki).

Both manifests include the add-on product declaration, use stable API modules, and require no beta APIs, experiments, cheats, or external dependencies. Fresh-world achievement verification remains documented in the project test plan.

## License

All Rights Reserved. Players, servers, Realms, and content creators have the permissions stated in [LICENSE.md](LICENSE.md). Minecraft is a trademark of Microsoft Corporation; this project is not affiliated with Microsoft or Mojang Studios.
