<img src="https://img.shields.io/github/downloads/BlaizerBrumo/SafeGuard/total?style=for-the-badge" alt="Downloads"/><br>
SafeGuard is a minecraft bedrock anti-cheat add-on with simple protection and customizable functions to use against hackers, it includes such things as:

## ======Modules======

- Anti CBE- Kills NPCs and command block minecarts to stop hackers from using command block exploit.



- Anti GMC- Sets non staff players back to survival



- Anti Lag- Kills entities in the world to clear lag(doesn't include pets)



- Anti Items- Clears un-obtainable items from non staff players, can also be customized



- Anti Grief- Clears all tnt and respawn anchors from player's inventory

- Anti 32k- Clears items with illegal enchants from non staff members


## =====Admin Commands=====

- Vanish- This function is a toggle command which puts you in and out of invisibility

- Summon NPC- Since the anti-cheat kills all NPCs, this command will summon an NPC at your location which will not die /function setup/summon_npc.

- Clearchat- Clear the chat, `/function admin_cmds/clearchat`

- Fake Leave- Sends a message like you left

- Custom commands, to view run `!help`

## =====Punishments=====

- Flagged- A tag which puts the person in adventure mode | /tag [name] add flagged to flag person | /tag [name] add unflag



- Freeze- Freezes selected person in place | /tag [name] add freeze to freeze | /tag [name] add unfreeze to remove



- Inventory Lock- Clears person inventory and puts un-removable items in their inventory | /tag [name] add inv_lock to inventory lock | /tag [name] add inv_unlock to remove inventory lock

- Enderchest wipe- Clears person's enderchest, /tag [name] add echest_wipe

- Enderchest ban- Doesn't allow person to use enderchests | /tag [name] add echest_ban to enderchest ban | /tag [name] add echest_unban to remove enderchest ban

- Ban- Bans people forever, cannot unban people yet | !ban [name]

- Softbans- Is the same as flag, but auto and bans them at a certain time. 5 minutes: /tag [name] add softban_five10 minutes: /tag [name] add softban_ten20 minutes: /tag [name] add softban_twen60 minutes: /tag [name] add softban_hour

## =====Helpful Features=====

- Auto Mod- Auto kicks people who obtain banned or illegal items

- Warnings- Can be checked through `/tag <name> add stats` and are used to auto ban

- Help Command- Gives a quick guide on the anticheat | /function setup/help

- Welcomer- Sends a message in chat when a person join the game for the first time

- Notify- Tells you when someone uses the anticheat commands



## =====Customize=====

- Custom banned items- Edit `config.js` file inside of scripts folder

## =====Settings(toggle)=====

**All the modules like anti cbe are now turned on through the /function settings/**

- Lock End- Teleports players away from the end portal and kills if they somehow enter

- Auto Mod- Auto kicks people

- No Shulker Barrels- Clears either shulker boxes, barrels, or both(made to prevent kits like 32k)

- Death Coords- Tells the person the coordinates at which they died

- Death Effect- Makes an effect when someone dies



## =====How to Use=====

1. Download the files from gihub release
2. If you want to customize, change the .mcpack to .zip, unzip files, change the things you want, zip it, and change .zip to .mcpack
3. Add the add-on to world/realm
4. Turn on Holiday Creator Features & Beta API
5. Run /function setup/setup
6. Toggle on all the modules you want in /function settings/
7. Enjoy!
