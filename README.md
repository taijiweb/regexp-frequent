# regexp-frequent

[Some frequently used regexp.]( http://www.cnblogs.com/zxin/archive/2013/01/26/2877765.html)

This package can be used independently, or be used as the registry for the npm package [rewrap](https://github.com/taijiweb/rewrap).

See [rewrap](https://github.com/taijiweb/rewrap) for more information.

## usage
  `npm install regexp-frequent`  
  `npm install rewrap`

```js
    const reBuiltins = require('regexp-frequent');
    const rewrap = require('rewrap');
    rewrap.registry(reBuiltins);
```

## document
  Just see index.js.
