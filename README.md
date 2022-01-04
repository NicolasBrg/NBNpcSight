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
![image](https://user-images.githubusercontent.com/30299182/148052427-433a4eb3-7e19-4502-a1d8-5439fba28086.png)
- **Position**: Word location
- **Type**: NPC Type (Nurse, Doctor, Trainer, Chat, ect...)
- **AreaSight**: Enable / Disable area detection
- **Distance**: Distance of detection
- **AI**: Enable / Disable NPC AI
- **ExecuteCommands**: Number of commands executed when a player is detected
- **VictoryCommands**: Number of commands executed when a player defeat a NPC Trainer.

## Detection type
> *Wools represent only detection and are not required.*
### Single
Detects players in the NPC direction. (locked NPC)
![image](https://user-images.githubusercontent.com/30299182/148052573-2a7807ae-0302-4aff-a318-303d3185c3c2.png)

### Multiple
Detect the players in the directions (``NORTH``, ``SOUTH``, ``EAST``, ``WEST``), NPC will fix the player during the detection. (Unlocked NPC)
![image](https://user-images.githubusercontent.com/30299182/148052700-942b7a36-fc33-491c-b1cd-a91c9c3fd19b.png)

### Area
Detects players in the zone regardless of direction.
![image](https://user-images.githubusercontent.com/30299182/148052806-11779e81-a918-4966-928b-11362354d95f.png)

## Commands format
> *For **Detection** commands and **Victory** commands*

Player name will replace text "**{PLAYER}**", color alias are available using "&" symbol.

Some alias are available to start commands:
- **BROAD**: Broadcast a message for all player on the server.
- **PM**: Send a private message to the current player
- **CLOSE**: Close UI if open
- **/**: Command who will be executed by the player
- **!**: Command who will be executed by the server

If no alias are provided, it's executed by server as normal command, you can use give and other commands.
