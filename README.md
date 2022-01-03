# NBNpcSight
A plugin that allows you to customize the NPC vision, create RP adventures or reproduce game scenarios very easily with this tool.

## Usage
If you have toggle enabled, just right click on an NPC (Pixelmon is required) to sight it or display his menu.

*Video soon*

## Commands
### /nbnpcsight_config \<Load / Save\>
> Permission: *nbnpcsight.config*

Force the loading/saving of the configuration.

### /togglenpcsight
> Permission: *nbnpclock.admin*

A toggle mod to enable or disable the lock mod for the administrator using the command.

## UI
![image](https://user-images.githubusercontent.com/30299182/147983284-7d75091b-30a6-490c-947a-00115abf2d43.png)
- **Position**: Word location
- **Type**: NPC Type (Nurse, Doctor, Trainer, Chat, ect...)
- **AreaSight**: Enable / Disable area detection
- **Distance**: Distance of detection
- **AI**: Enable / Disable NPC AI
- **ExecuteCommands**: Number of commands executed when a player is detected
- **VictoryCommands**: Number of commands executed when a player defeat a NPC Trainer.

## Detection type
### Single
Detects players in the NPC direction. (locked NPC)

### Multiple
Detect the players in the directions (``NORTH``, ``SOUTH``, ``EAST``, ``WEST``), NPC will fix the player during the detection. (Unlocked NPC)

### Area
Detects players in the zone regardless of direction.

## Commands format
> *For **Detection** commands and **Victory** commands*

Player name will replace text "**{PLAYER}**", color alias are available using "&" symbol.

Some alias are available to start commands:
- **BROAD**: Broadcast a message for all player on the server.
- **PM**: Send a private message to the current player
- **CLOSE**: Close UI if open

If no alias are provided, it's executed by server as normal command, you can use give and other commands.
