# GeyserMC Pterodactyl Stuff
This repo contains the eggs for GeyserMC and the docker images for auto update support used by the eggs, for Pterodactyl Panel.

## Geyser
### Geyser: Standalone
* Egg: `egg-geyser-m-c.json`
* Container: [`pterodactyl-geyser`](https://github.com/GeyserMC/pterodactyl-stuff/pkgs/container/pterodactyl-geyser)

### Geyser: Spigot + [PaperMC](https://papermc.io/)
* Egg: `egg-paper--geyser--floodgate.json`

### Geyser: Bungee + [Waterfall](https://papermc.io/)
* Egg: `egg-waterfall--geyser--floodgate.json`

### Geyser: Standalone + GeyserConnect
* Egg: `egg-geyser-connect.json`
* Container: Uses the geyser container and loads the extension in
