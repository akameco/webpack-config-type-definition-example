# webpack-config-type-definition-example
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)

## Usage

```
yarn add --dev @types/webpack
```

Add `@type import('webpack').Configuration` to your `webpack.config.js`.

```js
/**
 * @type import('webpack').Configuration
 */
module.exports = {
  mode: "development",
  entry: "./src/index.js",
  output: {
    filename: "bundle.js"
  }
};
```

## Wow!!

[![Image from Gyazo](https://i.gyazo.com/a89693c9ae68dfd3d6f4a889b970b910.gif)](https://gyazo.com/a89693c9ae68dfd3d6f4a889b970b910)

### What is this?

See [Type Checking JavaScript Files · TypeScript](https://www.typescriptlang.org/docs/handbook/type-checking-javascript-files.html#import-types)


## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table><tr><td align="center"><a href="http://akameco.github.io"><img src="https://avatars2.githubusercontent.com/u/4002137?v=4" width="100px;" alt="akameco"/><br /><sub><b>akameco</b></sub></a><br /><a href="https://github.com/akameco/eslint-checker/commits?author=akameco" title="Code">💻</a> <a href="https://github.com/akameco/eslint-checker/commits?author=akameco" title="Documentation">📖</a> <a href="https://github.com/akameco/eslint-checker/commits?author=akameco" title="Tests">⚠️</a> <a href="#infra-akameco" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td></tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind welcome!

## License

MIT © [akameco](http://akameco.github.io)
