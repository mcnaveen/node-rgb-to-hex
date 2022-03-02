# Convert RGB to HEX
:unicorn: Simple utility to convert RGB Values to HEX color codes

![Build](https://github.com/mcnaveen/node-rgb-to-hex/workflows/Build/badge.svg)

![Extract Email Domain Name](./image/cover.png)

### :package: Requirements
Node.js 12.x LTS or 14.x LTS

### :sparkles: Installation

Install the NPM Package with the below command:
```
npm install node-rgb-to-hex --save
``` 

 (or)

Install with Yarn:
```
yarn add node-rgb-to-hex
```

### :pen: Usage

Import the module in your project:

```javascript
// Commonjs Import
var rgbToHex = require("node-rgb-to-hex");

// or ES6 import
import rgbToHex from "node-rgb-to-hex";
```

### :bulb: Example

Pass the RGB value to the function

```javascript
import rgbToHex from "node-rgb-to-hex";

const hex = rgbToHex(255, 255, 255)
console.log(hex);

```

### :ballot_box_with_check: Example Output
```
#ffffff
```
---


#### :green_heart: Message

I hope you find this useful. If you have any questions, please create an issue.