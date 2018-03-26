# Project Breakpoint: Easy Canvas

Easy Canvas is a library of helper functions that are intended to simplify Canvas functions.

**DO NOT DOWNLOAD FROM NPM OR GITHUB**

This project is very early in development and isn't ready for use.  I'm posting it on Github for my own storage and version control.  There's one edition on NPM that I put up as a test.  Neither edition is ready for use at this time.

# Installation

```npm install pb-easycanvas --save```

```javascript
const EasyCanvas = require('pb-easycanvas');
```

# Example Usage:

```javascript
props = {
    string: "This is fun!",
    fontsize: 18,
    color: 'red',
    just: 'center',
    x: 0,
    y: 0
}
EasyCanvas.drawText(ctx,props);
```

# Author
Jonathan Kuhl 2017