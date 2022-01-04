# NBNpcSight
A forge mod that grants the ability to give NPC's vision, area detection, as well as optional command execution and or victory commands!
Using the UI you are able to select from 3 different detection methods, directional line of sight, multiple lines of sight, or area sight (a definable area around the npc)
If you have the mod NPC lock, a 4th method is available, for locking the npc in any line of sight and locking the npc's into only looking that way.
All of this is done through one super easy to use UI!

## Usage
If you have toggle enabled, just right click on an NPC (Pixelmon is required) to sight it or display his menu.

*Video soon*

## Commands
### /nbnpcsight_config \<Load / Save\>
> Permission: *nbnpcsight.config*

Load the config (if you made changes via it)
A force save of the config (shouldn't be necessary, as it auto saves)

### /togglenpcsight
> Permission: *nbnpclock.admin*

Toggle command to enable or disable the UI being brought up while right clicking a NPC!
Simply run the command /togglenpcsight and right click the npc's you would like to edit. 
When finished type /togglenpcsight once more to exit the edit mode!

## UI
![image](https://user-images.githubusercontent.com/30299182/148052427-433a4eb3-7e19-4502-a1d8-5439fba28086.png)
- **Position**: World/DIM & coordinates
- **Type**: NPC Type (Chat, Nurse, Battle, etc)
- **AreaSight**: Enable / Disable area detection
- **Distance**: Distance of detection (in blocks)
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
