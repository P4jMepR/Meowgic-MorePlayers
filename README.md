# Meowgic-MorePlayers

Increases the [Meowgic](https://store.steampowered.com/app/4252290/Meowgic/) lobby player cap from 4 to 8 and ensures every player has the starting gear needed to play.

- Raises the online lobby limit from default to 8
- Duplicates the starting magic wands so all players can equip one
- Duplicates the starting Spell List items so all players can pick one up
- Mod require Host-only install for the lobby cap; wand/Spell List duplication requires every player to run the same patched DLL (they won't see them otherwise, but game will work just fine)

![Meowgic Mod](/MeowgicMod.png)

## Installation

1. Replace `Assembly-CSharp.dll` that is located at `steamapps\common\Meowgic\Meowgic_Data\Managed` (game folder) with the patched one from this repo. You can do it by just by replacing the directory if you preffer
2. All players in the lobby must use the same patched DLL.
