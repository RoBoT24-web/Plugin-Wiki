# Vehicle Build Restrictor: Commands & Permissions

## Management Commands

| Command | Permission | Description |
|---|---|---|
| `/vehiclebuild` (`/vbuild`) | `vehiclebuild.manage` | Base management command. |
| `/vehiclebuild group create <permission>` | `vehiclebuild.manage` | Create permission group. |
| `/vehiclebuild group delete <permission>` | `vehiclebuild.manage` | Delete permission group. |
| `/vehiclebuild group list [permission]` | `vehiclebuild.manage` | List groups or limits. |
| `/vehiclebuild set <permission> <itemId> <quantity>` | `vehiclebuild.manage` | Add/update item cap. |
| `/vehiclebuild remove <permission> <itemId>` | `vehiclebuild.manage` | Remove item cap. |

## Config-Based Permissions

| Permission | Description |
|---|---|
| `vehiclebuild.manage` | Required for `/vehiclebuild` commands. |
| `v.bypass.all` (default name) | Bypass all plugin restrictions. |
| `v.bypass.building` (default name) | Bypass global vehicle-building block. |
| Group permissions (example: `v.bypass.police`) | Apply configured per-item limits for that group. |
