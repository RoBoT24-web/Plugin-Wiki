# CCRP: Commands & Permissions

## Moderation

| Command | Permission | Description |
|---|---|---|
| `/ban <name> <reason>` | `ccrp.ban` | Permanently bans a player. |
| `/ban <name> <reason> <duration>` | `ccrp.ban` | Temporarily bans a player (`m/h/d`). |
| `/kick <name> <reason>` | `ccrp.kick` | Kicks an online player. |
| `/warn <name> <reason>` | `ccrp.warn` | Adds a warning. |
| `/warns [name]` | `ccrp.warns` (`ccrp.warns.other` for others) | Shows warning info. |
| `/removewarn <name> <reason>` | `ccrp.removewarn` | Removes one warning. |
| `/unban <Steam64ID> <reason>` | `ccrp.unban` | Unbans a Steam account. |
| `/god [name]` | `ccrp.god` (`ccrp.god.others` for others) | Toggles godmode. |
| `/vanish [name]` | `ccrp.vanish` (`ccrp.vanish.others` for others) | Toggles vanish. |
| `/tphere <name>` | `ccrp.tphere` | Teleports player to you. |

## Admin / Utility

| Command | Permission | Description |
|---|---|---|
| `/duty` | `ccrp.duty` (+ duty-group permission) | Toggles duty status. |
| `/playtime [name]` | `ccrp.playtime` | Shows playtime. |
| `/teleport <player-or-location>` (`/tp`) | `ccrp.teleport` | Teleport to player/location. |
| `/teleport <x> <y> <z>` | `ccrp.teleport` | Teleport to coordinates. |

## Staff Tools (Build / Camera)

| Command | Permission | Description |
|---|---|---|
| `/freecam` | `CCRPbuild.freecam` | Toggles freecam controls. |
| `/editor` | `CCRPbuild.editor` | Toggles object editor (F6). |
| `/spectate` | `CCRPbuild.spectate` | Toggles player-name/map visibility. |

## Items / Vehicles

| Command | Permission | Description |
|---|---|---|
| `/i <id-or-name> [amount]` (`/give`) | `ccrp.i` (+ `ccrp.i.<n>`) | Gives item by ID/name. |
| `/v <id-or-name>` (`/vehicle`) | `ccrp.v` | Spawns vehicle by ID/name. |

## Blacklist Management

| Command | Permission | Description |
|---|---|---|
| `/blacklist add <give\|pickup\|both\|vehicle> <id> <bypass-permission>` | `ccrp.blacklist.manage` | Adds blacklist entry. |
| `/blacklist remove <give\|pickup\|both\|vehicle> <id>` | `ccrp.blacklist.manage` | Removes blacklist entry. |

## Wrecking Ball

!!! warning
    Always run a `scan` first to preview targets before using `confirm`.

| Command | Permission | Description |
|---|---|---|
| `/wreck <filter> <radius> [username\|Steam64]` | `ccrp.wreck` | Queue targets by category filter. |
| `/wreck scan <filter> <radius> [username\|Steam64]` | `ccrp.wreck` | Preview matching targets. |
| `/wreckitem <id[,id...]> <radius> [username\|Steam64]` | `ccrp.wreck` | Queue targets by exact item IDs. |
| `/wreckitem scan <id[,id...]> <radius> [username\|Steam64]` | `ccrp.wreck` | Preview ID matches. |
| `/wreck confirm` | `ccrp.wreck` | Start destruction. |
| `/wreck abort` | `ccrp.wreck` | Cancel queued/active request. |
