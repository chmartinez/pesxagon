# pesxagon

[![npm (scoped)](https://img.shields.io/npm/v/@chmartinez35/pesxagon.svg)](https://www.npmjs.com/package/@chmartinez35/pesxagon)

Renders an hexagon like the ones from PES

![example](https://2.bp.blogspot.com/_BDntoozHszs/S3ZIqr27OQI/AAAAAAAAAQY/pSnzw5pct4s/s320/eng2.bmp)

## Install

```
$ npm install @chmartinez35/pesxagon
```

## Usage
```
const Pesxagon = require('@chmartinez35/pesxagon');
const stats = [
    {name: 'Attack', abbrev: 'ATK', value: 90},
    {name: 'Technique', abbrev: 'TEC', value: 70},
    {name: 'Stamina', abbrev: 'STA', value: 80},
    {name: 'Defense', abbrev: 'DEF', value: 30},
    {name: 'Power', abbrev: 'POW', value: 85},
    {name: 'Speed', abbrev: 'SPD', value: 91},
];

const pesxagon = Pesxagon('containerId'); // will setup the pesxagon with minimal configuration;

pesxagon.draw(stats);

// MAGIC! 🧙🏽‍♂️

```