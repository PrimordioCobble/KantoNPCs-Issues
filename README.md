# KantoNPCs - Issue Tracker

Please make sure you are using the correct Minecraft, Fabric, Fabric API, Java, and Cobblemon versions for the KantoNPCs release you installed.

Also try to reproduce the issue with the smallest possible setup. If the bug only happens on a server, please test whether it also happens in singleplayer or a local test world.

## Include This Information

When reporting a bug, please include:

- KantoNPCs version
- Minecraft version
- Fabric Loader version
- Fabric API version
- Cobblemon version
- Java version
- Singleplayer, LAN, or dedicated server
- Full mod list or modpack name
- `latest.log`
- Crash report, if there is one
- Clear steps to reproduce the issue
- Screenshots or a short video, if useful

## NPC Issues

If the issue is related to an NPC, please include:

- NPC type: Dialog NPC, Battle NPC, Rival NPC, Mart NPC, Trader NPC, or Move Tutor NPC
- Whether the NPC was newly created or already existed before updating
- Whether the NPC has custom skin/model settings
- Whether the NPC has a start, end, post, or yes/no dialogue flow
- Whether the issue happens before or after restarting the world/server
- Any relevant dialogue ID, reward item, command, shop entry, trade setup, battle setup, or tutor move

You do not need to paste every NPC setting, but include the fields that seem related to the bug.

## Battle Issues

If the issue is related to Battle NPCs or Rival NPCs, please include:

- The configured NPC team
- The player's team, if relevant
- Pokémon levels
- Whether moves were configured manually or automatically
- Whether the issue happened before, during, or after the battle
- Whether the post-battle dialogue opened
- Whether item rewards, commands, money rewards, cooldowns, or Amulet Coin were involved
- Logs from the moment the battle started and ended

## Mart, Trader, or Move Tutor Issues

For Mart NPC issues, include the buy/sell entry that caused the problem, the price/cost setup, and whether the issue happened when buying, selling, hovering, or editing.

For Trader NPC issues, include the requested Cobblemon, the given Cobblemon, the player's party order, and which party slot was selected.

For Move Tutor NPC issues, include the configured move, the selected Cobblemon, and whether that Cobblemon should normally be able to learn the move.

## Skin or Model Issues

If the issue is related to skins or models, please include:

- Skin file name
- Whether the file is inside `config/kantonpcs/skins`
- Whether you used the in-game refresh button
- Whether the issue happens only for one player or for everyone
- A screenshot of the NPC if possible

## Not Accepted Here

Please do not open issues for:

- Requests for the private source code
- Reuploads of the mod
- Unrelated Cobblemon bugs
- General Minecraft support unrelated to KantoNPCs
- Problems caused by editing the jar file directly

## Contact

For direct feedback, ideas, or project-related questions, you can send a direct message to **cobblekanto** on Discord.
