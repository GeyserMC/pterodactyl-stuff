# GeyserMC Pterodactyl Stuff
This repo contains the eggs for GeyserMC and the docker images for auto update support used by the eggs, for Pterodactyl Panel.

## Paper + Geyser / Floodgate eggs

The Paper eggs use the [Paper API v3](https://docs.papermc.io/misc/downloads-service/) (`fill.papermc.io`) and [ptero-eggs](https://github.com/ptero-eggs/yolks) Java images. Paper, Geyser, and Floodgate are fetched at **install/reinstall** time.

### Eggs

#### [PaperMC](https://papermc.io/downloads/paper) + Geyser + Floodgate
* Egg: `egg-paper--geyser--floodgate.json`

#### [PaperMC](https://papermc.io/downloads/paper) + Floodgate
* Egg: `egg-paper--floodgate.json`

## Geyser
### [Velocity](https://papermc.io/downloads/velocity) + Geyser + Floodgate
* Egg: `egg-velocity--geyser--floodgate.json`

### Geyser: Standalone
* Egg: `egg-geyser-m-c.json`
* Container: [`pterodactyl-geyser`](https://github.com/GeyserMC/pterodactyl-stuff/pkgs/container/pterodactyl-geyser)

### Geyser: Standalone + [GeyserConnect](https://github.com/GeyserMC/GeyserConnect)
* Egg: `egg-geyser-connect.json`
* Container: Uses the normal Pterodactyl Geyser container and loads the extension in
