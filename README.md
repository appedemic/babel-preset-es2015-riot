# babel-preset-es2015

> Babel preset for all es2015 plugins, with allowTopLevelThis enabled

## Install

```sh
$ npm install --save-dev babel-preset-es2015-riot
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-riot"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015-riot
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-riot"]
});
```
