# dinosauregg

<span style="font-size: 120px">🦕</span>🥚
Common scaffolding based on egg.js construction

## QuickStart

```bash
$ npm install
$ npm test
```

publish your framework to npm, then change app's dependencies:

```js
// {app_root}/index.js
require('dinosauregg').startCluster({
  baseDir: __dirname,
  // port: 7001, // default to 7001
});

```

## Questions & Suggestions

Please open an issue [here](https://github.com/eggjs/egg/issues).

