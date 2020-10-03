# SquadMC - Squad基于地图的迫击炮计算器

SquadMC 是基于地图的迫击炮高程和方位角计算器 [*Squad*](http://joinsquad.com/).

![IPhone 5 Screenshot](./public/img/iphone_screenshot.png)

## 链接

 * **目前版本: https://squadmc.ende.pro**
 * a version for the game [*Post Scriptum*](http://postscriptumgame.com/): **https://postscriptum.squadmc.ende.pro**
   * shorter url: **https://psmc.ende.pro**
   * I don't own the game myself, so I need feedback from other players
   * check out the [postscriptum branch](https://github.com/Endebert/squadmc/tree/postscriptum) for the code
 * map files are stored in another repository: https://github.com/Endebert/squadmc-maps
## 特点
 * 使用高度图和迫击炮弹弹道功能，高度精确的仰角和方位角计算
 * 针对移动设备进行了优化
 * 快速放置和拖动迫击炮、目标以及FOB标记
 * 支持多个迫击炮，目标和FOB标记，并允许在它们之间进行切换
 * 最大 & 最小迫击炮范围标识
 * 最大构建范围和到下一个FOB的最小距离
 * 网格（可切换）
 * 坐标计算
 * 位置显示（可切换）
 * 高度图（可切换）


## installation

### Installation Prerequisites

 * you need a recent NodeJS version installed on your machine. Get it [here.](https://nodejs.org/en/)
 * install yarn for a faster installation:
   ```
   npm install -g yarn
   ```

### Cloning repository & installing dependencies

```
git clone https://github.com/MrSeven590/squadmc.git
cd squadmc
yarn install
```

### Running development mode

For development mode with hot-reload, execute:
```
yarn run serve
```

### Building production version

For an optimized build ready for deployment, execute:
```
yarn run build
```
The build will be contained in the `/dist` folder.

## Contributors
 * [Trikolon](https://github.com/Trikolon)
 * [Kalliser](https://github.com/Kalliser)
 * [TopMak](https://github.com/TopMak)
 * [ansarto](https://github.com/ansarto)

## Attributions
 * Keypad grid originally based on [Leaflet.SimpleGraticule](https://github.com/ablakey/Leaflet.SimpleGraticule), but not much is left from the original code
 * Special thanks to the people over at [www.airpressuretendency.net](https://www.airpressuretendency.net/fcsquad/squadmaps/). Their interactive maps were the inspiration for this project.
 * UI powered by [Vue.js![Vue.js](./public/img/logos/logo_vuejs.png)](https://vuejs.org/) and [Vuetify![Vue.js](./public/img/logos/logo_vuetify.png)](http://vuetifyjs.com/)
 * Maps © [Offworld Industries](http://joinsquad.com/), powered by [![Leaflet](./public/img/logos/logo_leaflet.png)](https://leafletjs.com/)
 * Tested with [![BrowserStack](./public/img/logos/logo_browserstack.png)](https://www.browserstack.com/)
