# GeyserMC Pterodactyl Stuff
This repo contains the eggs for GeyserMC and the docker images for auto update support used by the eggs, for Pterodactyl Panel.

## Geyser
### Geyser: Standalone
* Egg: `egg-geyser-m-c.json`
* Container: [`pterodactyl-geyser`](https://github.com/GeyserMC/pterodactyl-stuff/pkgs/container/pterodactyl-geyser)

### Geyser: Spigot + Floodgate + [PaperMC](https://papermc.io/downloads/paper)
* Egg: `egg-paper--geyser--floodgate.json`

### Geyser: Bungee + Floodgate + [Waterfall](https://papermc.io/downloads/waterfall)
* Egg: `egg-waterfall--geyser--floodgate.json`

### Geyser: Velocity + Floodgate + [Velocity](https://papermc.io/downloads/velocity)
* Egg: `egg-velocity--geyser--floodgate.json`

### Geyser: Standalone + [GeyserConnect](https://github.com/GeyserMC/GeyserConnect)
* Egg: `egg-geyser-connect.json`
* Container: Uses the normal Pterodactyl Geyser container and loads the extension in

## Floodgate
### Floodgate: Spigot + [PaperMC](https://papermc.io/downloads/paper)
* Egg: `egg-paper--floodgate.json`