# BedwarsRelCloudNetAddon
 
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/330bf38601a34c7dbd9d270a4da7da23)](https://www.codacy.com/app/Fridious/BedwarsRel-CloudNet-Addon?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Fridious/BedwarsRel-CloudNet-Addon&amp;utm_campaign=Badge_Grade) 
[![DKPlugins Discord](https://discordapp.com/api/guilds/513441444959223809/embed.png)](https://discord.gg/PawBsVy)

## SpigotMc
<https://www.spigotmc.org/resources/bedwarsrel-cloudnet-addon.62734/>

## Introduction
This is a simple BedwarsRel addon for CloudNet with resource voting. It only works on a single server, so the arena mode from BedwarsRel doesn't work.

## Functions
On start of the plugin, the motd changed to the map name for displaying the map on the signs and the max players of the server changed to the max players of the bedwars game
If the bedwars game starts, the game changed the state to ingame of cloudnet to start a new server automatically and hide the server in the lobbies on the signs.
You can enable to get coins on kill, finalkill, win and target block destroy in the config.
Also the slots changed to default 100, in order to join spectators. Also you can change the 100 spectator slots.
It has a Stats command, which executed the intern bw stats command of BedwarsRel.
You can enable resource voting(for example gold voting) and you can force resource voting with /forceresource <true, false>.

## Dependencies
-   CloudNet <https://www.spigotmc.org/resources/cloudnet-the-cloud-network-environment-technology.42059/>
-   BedwarsRel <https://www.spigotmc.org/resources/bedwars-rel.6799/>
-   Vault <https://www.spigotmc.org/resources/vault.34315/> (Optional)

## Discord
[![Join DKPlugins Discord](https://discordapp.com/api/guilds/513441444959223809/embed.png?style=banner2)](https://discord.gg/PawBsVy)

## Developer
-   BedwarsPlayerFinalKilledEvent
