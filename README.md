# GeyserMC Pterodactyl Stuff
This repo contains the eggs for GeyserMC and the docker images for auto update support used by the eggs, for Pterodactyl Panel.

## Geyser
### [PaperMC](https://papermc.io/downloads/paper) + Geyser + Floodgate
* Egg: `egg-paper--geyser--floodgate.json`

### [Waterfall](https://papermc.io/downloads/waterfall) + Geyser + Floodgate
* Egg: `egg-waterfall--geyser--floodgate.json`

### [Velocity](https://papermc.io/downloads/velocity) + Geyser + Floodgate
* Egg: `egg-velocity--geyser--floodgate.json`

### Geyser: Standalone
* Egg: `egg-geyser-m-c.json`
* Container: [`pterodactyl-geyser`](https://github.com/GeyserMC/pterodactyl-stuff/pkgs/container/pterodactyl-geyser)

### Geyser: Standalone + [GeyserConnect](https://github.com/GeyserMC/GeyserConnect)
* Egg: `egg-geyser-connect.json`
* Container: Uses the normal Pterodactyl Geyser container and loads the extension in

## Floodgate (Only)
### [PaperMC](https://papermc.io/downloads/paper) + Floodgate
* Egg: `egg-paper--floodgate.json`
