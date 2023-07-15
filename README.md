# Homiecraft

A modpack designed to be an easy intro to modded Minecraft. Centered around the excellent Create mod with  additional decoration and world gen mods keeps everyone engaged. Whether tinkering with machines, building expansive cities or exploring brand new biomes and dungeons. 

## Disclaimer

This mod pack is currently in **alpha**. The mod list is not fully solidified yet and mods may be added or removed between versions.

## Packwiz

This modpack is built using [Packwiz](https://packwiz.infra.link/). Install the CLI to use the commands below:

### Add a new mod

Prefer adding from Modrinth (`mr`) over CurseForge (`cf`) as Modrinth is the primary source for this pack.

```bash
packwiz mr add create-fabric
packwiz cf add create-fabric
```

### Export the pack

This will download all mod jars to the `/mods` folder and create an `.mrpack` file. This file can be imported into the lanucher of your choice.

```bash
packwiz mr export
```

### Update all mods

```bash
packwiz update --all
```

### Update a specific mod

```bash
packwiz update create-fabric
```

### Refresh Packwiz hashes

```bash
packwiz refresh
```
