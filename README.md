# is-pptx
Detect pptx file type from buffer

## Install

```
npm install is-pptx
```

## Usage

```js
const fs = require('fs');
const isPptx = require('is-pptx');

const file = fs.readFileSync('example.pptx');

console.log(isPptx(file)); // > true
```
