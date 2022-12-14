# WorkAdventure MrOtek3S Map 

![map](./map.png)

Own map for [WorkAdventure](https://workadventu.re).


## Structure
* **tilesets** : All tilesets
* **public** : Static files
* **src** : All TypeScript/Javascript scripts
* **map.(json/tmj)** : Map file
* **map.png** : Image displayed on README.md and on the map infos in-game

## Requirements

Node.js version >=16

## Installation

With npm installed (comes with [node](https://nodejs.org/en/)), run the following commands into a terminal in the root directory of this project:

```shell
npm install
npm run dev
```

## Test optimized map
You can test the optimized map as you do in production:
```sh
npm run build
npm run preview
```

## Licenses

This project contains multiple licenses as follows:

* [Code license](./LICENSE.code) *(all files except those for other licenses)*
* [Map license](./LICENSE.map) *(`map.json` and the map visual as well)*
* [Assets license](./LICENSE.assets) *(the files inside the `src/assets/` folder)*

### About third party assets

If you add third party assets in your map, do not forget to:
1. Credit the author and license with the "tilesetCopyright" property present in the properties of each tilesets in the `map.json` file
2. Add the license text in LICENSE.assets
