# poi-preset-mobx-react-js

## Features

- It uses the same Babel config that create-react-app uses
- react-hot-loader@3
- babel-transform-decorators-legacy
- babel-transform-class-properties

## Install

```bash
yarn add react react-dom
yarn add navx2810/mobx-react --dev
```

## Usage

```js
module.exports = {
  presets: [
    require('poi-preset-mobx-react')()
  ]
}
```