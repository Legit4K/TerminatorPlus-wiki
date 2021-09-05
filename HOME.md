### Plugin Description
**TerminatorPlus** is a Spigot plugin that allows the creation of server-side player bots. Unlike many NPC plugins that already exist, this project has an emphasis on making the bots as human-like as possible.

### Supported Versions
During the Beta phase, Minecraft Server Version 1.16.5 is the single compatible version. 1.17 support will likely roll out in the first stable release.

### Getting Started
* [Download the plugin here](https://discord.gg/horsenuggets)
* Place the plugin in your server plugins folder
* Restart your minecraft server
* Try out `/terminatorplus`

### Compiling
* Clone the repo to your computer
* [Install and setup Maven here](https://maven.apache.org/install.html)
* Enter into the repo directory
* run `mvn clean package`
* find artifacts in **target** folder

### Commands
These are all the commands that are currently available in this plugin.
* `<>` **Required**
* `[]` **Optional**

`/terminatorplus`
> View plugin information

`/bot create <name> [skin]`
> Create a bot based on the block you are looking at.
>> **Example:** `/bot create fat`

`/bot multi <amount> <name> [skin]`
> Create multiple bots at once
>> **Example:** `/bot multi 10 bob Dream`

`/bot give <item>`
> Give the specified item to all bots
>> **Example:** `/bot give netherite_sword`

`/bot armor <armor-tier>`
> Give the specified armor to all bots
>> **Example:** `/bot armor iron`

`/bot range <attack-range>`
> Change how far the bot can reach in combat
>> **Example:** `/bot range 2`

`/bot block <block>`
> Change the placement block for all bots
>> **Example:** `/bot block diamond_block`

`/bot info [name]`
> Gather information about an existing bot
>> **Example:** `/bot info bob`

`/bot reset`
> Remove all loaded bots from the server

`/bot settings`
> Change bot behaviour and access plugin config
>> **Example:** `/bot settings setgoal nearest_bot`

`/bot debug`
> Execute dev commands
>> **Example:** `/bot debug tpall()`

`/ai random <amount> <name> [skin]`
> Create bots with random neural networks (ai) collecting data
>> **Example:** `/bot random 10 bob`

`/ai reinforcement <size> <name> [skin]`
> Begin an AI Training Session
>> **Example:** `/bot reinforcement 5 bob`

`/ai stop`
> Stop all AI Training Sessions

`/ai info <name>`
> Display the neural net info of a bot
>> **Example:** `/ai info bob`