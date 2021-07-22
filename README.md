# PixzaRPG - Data Pack Documentation

Documentation on how to create your own data packs for PixzaRPG. 

## Getting Started

For examples, see [PixzaCore-Data](https://github.com/PixzaRPG/PixzaCore-Data) which is the default data pack used.
**All data packs require a `manifest.json` file in the root directory**

| Type            | Docs | Description |
| --------------- | ---- | ----------- |
| `manifest.json` | [here](./manifest.md) | Contains general information about the datapack |  
| `/regions/**/*.json` | [here](./regions/regions.md) | World regions and region flags |
| `/items/**/*.json` | [here](./items/items.md) | Items and item components |

## Deploying

Copy the folder your data pack is in into the `packs` folder in the PixzaRPG plugins folder.