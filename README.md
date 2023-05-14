# ❤️ Kâzii's Indicators

## ⚠️ Quick Pre-Caution
This datapack is mostly automated by itself, but there is a pre-caution that needs to be taken:
Make sure coordinates from 0 255 0 to 1 256 0 are cleared with no obstructions.

## 💻 Performance Rating
Recommended for mid-end to high-end PCs,
strictly advising against low-end PCs, it handles fairly well with a mid-end to high-end PC, lower-end ones would start to form a slower gameplay.

Recommended for high-end servers.
mid-end and low-end servers may have trouble running this depending on the amount of players.

## 📜 Quick Overview
- Holds up to 2034 name labels (aka. Maximum Storage Array Limit)
- Has health indicators
- Has block data indicators
- Has damage & heal indicators
- Has short kill amount indicators for the players
- Variable name labels (both by a name tag and when spawned in with a name)

## ⚙️ Intended-Use
This datapack is intended for mainly-survival, especially with new worlds.
Already existing worlds should not be affected by it as much with how it was built.

### Strongly advise against installing this datapack into a minigame or map in any type.
It can lead to many incompatibility issues:
especially loss of names, not intended name changes, overall can cause lag with many other systems in the minigame / map.

## ⚠️ Warnings
When installed and implemented, the game will slow down for rougly 5 to 10 seconds to store all currently existing name labels. (cannot garantuee full name saves)
For larger worlds, the game would maybe slow down for over 15 seconds, it all comes down to how many entities have a name assigned in your current world.

When you decide to remove the datapack, please run `/trigger uninstall_kz-indicators`,
give it a few seconds and it should be done uninstalling, you can afterwards remove it from the files if `/reload` hasn't been ran.

### Do not spam `/reload` and `/trigger uninstall_kz-indicators`
Spamming these commands can cause many disruptions mid-operating and potentially lose names, etc..

## 🏷️ Name Slots
If you decide to get rid of your name slots, then run `/trigger reset_names_kz-indicators`,
this will clear out the entire storage array, get rid of all names (they will not be reverted to their Vanilla state, complete loss) and reset the ID system.
Do not spam this command.

## 👥 Multiplayer
This datapack is multiplayer-friendly (at least I hope with the way I tested it), you may add it to a multiplayer server.

# 💫 Enjoy the datapack.
