# react-works 

Monorepo for React components

[![Gitter](https://img.shields.io/gitter/room/nkbt/help.svg?style=flat-square)](https://gitter.im/nkbt/help)
[![CircleCI](https://img.shields.io/circleci/project/nkbt/react-works/master.svg?style=flat-square)](https://circleci.com/gh/nkbt/react-works/tree/master)
[![Dependencies](https://img.shields.io/david/nkbt/react-works.svg?style=flat-square)](https://david-dm.org/nkbt/react-works)
[![Dev Dependencies](https://img.shields.io/david/dev/nkbt/react-works.svg?style=flat-square)](https://david-dm.org/nkbt/react-works#info=devDependencies)



## Packages

|package|npm|
|---|---|
|[packages/bulkhead](./packages/bulkhead)|[![react-bulkhead](https://img.shields.io/npm/v/react-bulkhead.svg?style=flat-square&label=react-bulkhead)](https://www.npmjs.com/package/react-bulkhead)|
|[packages/element-resize](./packages/element-resize)|[![react-element-resize](https://img.shields.io/npm/v/react-element-resize.svg?style=flat-square&label=react-element-resize)](https://www.npmjs.com/package/react-element-resize)|
|[packages/swap](./packages/swap)|[![react-swap](https://img.shields.io/npm/v/react-swap.svg?style=flat-square&label=react-swap)](https://www.npmjs.com/package/react-swap)|
|[packages/interval](./packages/interval)|[![react-interval](https://img.shields.io/npm/v/react-interval.svg?style=flat-square&label=react-interval)](https://www.npmjs.com/package/react-interval)|
|[packages/page-click](./packages/page-click)|[![react-page-click](https://img.shields.io/npm/v/react-page-click.svg?style=flat-square&label=react-page-click)](https://www.npmjs.com/package/react-page-click)|
|[packages/normalized-select](./packages/normalized-select)|[![react-normalized-select](https://img.shields.io/npm/v/react-normalized-select.svg?style=flat-square&label=react-normalized-select)](https://www.npmjs.com/package/react-normalized-select)|
|[packages/text-filter](./packages/text-filter)|[![react-text-filter](https://img.shields.io/npm/v/react-text-filter.svg?style=flat-square&label=react-text-filter)](https://www.npmjs.com/package/react-text-filter)|



## Development and testing

### Install

Currently is being developed and tested with the latest `Node 8` on `OSX`.

```bash
git clone git@github.com:nkbt/react-works.git
cd react-works
yarn install
```

### Run tests for all packages

```bash
# to run eslint for all packages
yarn lerna run lint

# to run tests for all packages
yarn lerna run test

# to run end-to-end tests for all packages
yarn lerna run e2e
```

### Run package example

To run example covering all package features, use `yarn start`, which will compile `example/index.js`

```bash
cd packages/package-name
yarn start

# then
open http://localhost:8080
```

### Test one package only

```bash
cd packages/package-name

# to run lint
yarn lint

# to run tests
yarn test
```

## License

MIT
