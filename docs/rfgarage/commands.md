# RFGarage: Commands & Permissions

## Commands

| Command | Permission | Description |
|---|---|---|
| `/garageadd [vehicleName]` (`/gadd`, `/ga`) | `garageadd` | Stores current/targeted vehicle in garage. |
| `/garages` (`/gg`, `/glist`) | `garages` | Lists garage vehicles. |
| `/garageretrieve <vehicleName\|number>` (`/gret`, `/gr`) | `garageretrieve` | Retrieves stored vehicle. |
| `/garageadmin <list\|wipe\|del> <player> [id/name]` (`/gadmin`) | `garageadmin` | Manage another player's garage. |
| `/garagemigrate <from> <to>` (`/gm`) | `garagemigrate` | Migrate storage backend. |

## Extra Permissions

| Permission | Description |
|---|---|
| `garageslot.<slots>` | Garage slot limit override. |
| `garagedrown` | Auto-store drowned vehicles (if enabled). |
| Blacklist `BypassPermission` values | Bypass matching blacklist rules. |
