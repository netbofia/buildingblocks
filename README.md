# buildingblocks
NPM package with utilits to use bootstrap and build html on the fly



## Webpack 
in src/index.js
To export each function
```js
const buildingblocks=require("@netbofia/buildingblocks")
Object.keys(buildingblocks).forEach(key=>window[key]=buildingblocks[key])
```
or to export buidlingblocks only:
```js
const buildingblocks=require("@netbofia/buildingblocks")
window.buildingblocks=buildingblocks
```