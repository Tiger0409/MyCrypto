# MyCrypto Beta (VISIT [MyCryptoHQ/mycrypto.com](https://github.com/MyCryptoHQ/mycrypto.com) for the current site)<br/>Just looking to download? Grab our [latest release](https://github.com/MyCryptoHQ/MyCrypto/releases)

[![Greenkeeper badge](https://badges.greenkeeper.io/MyCryptoHq/MyCrypto.svg)](https://greenkeeper.io/)
[![Coverage Status](https://coveralls.io/repos/github/MyCryptoHQ/MyCrypto/badge.svg?branch=develop)](https://coveralls.io/github/MyCryptoHQ/MyCrypto?branch=develop)

## Running the App

This codebase targets Node 8.9.4 (LTS). After `npm install`ing all dependencies (You may be required to install additional system dependencies, due to some node modules relying on them) you can run various commands depending on what you want to do:

#### Development

```bash
# node module install
npm install
```


```bash
# run app in dev mode in browser, rebuild on file changes
npm run dev
```

```bash
# run app in dev mode in electron, rebuild on file changes
npm run dev:electron
```

#### Build Releases

```bash
# builds the production server app
npm run build
```


## Folder structure:

```
│
├── common
│   ├── actions - Application actions
│   ├── api - Services and XHR utils
│   ├── assets - Images, fonts, etc.
│   ├── components - Components according to "Redux philosophy"
│   ├── config - Various config data and hard-coded json
│   ├── containers - Containers according to "Redux philosophy"
│   ├── libs - Framework-agnostic libraries and business logic
│   ├── reducers - Redux reducers
│   ├── sagas - Redux sagas
│   ├── sass - SCSS styles, variables, mixins
│   ├── selectors - Redux selectors
│   ├── translations - Language JSON dictionaries
│   ├── typescript - Typescript definition files
│   ├── utils - Common use utility functions
│   ├── index.tsx - Entry point for app
│   ├── index.html - Html template file for html-webpack-plugin
│   ├── Root.tsx - Root component for React
│   └── store.ts - Redux reducer combiner and middleware injector
├── electron-app - Code for the native electron app
├── jest_config - Jest testing configuration
├── spec - Jest unit tests, mirror's common's structure
├── static - Files that don't get compiled, just moved to build
└── webpack_config - Webpack configuration
```

### More information is available on the [Wiki Pages](https://github.com/MyCryptoHQ/MyCrypto/wiki)

## Thanks & Support

<a href="https://browserstack.com/">
<img src="https://i.imgur.com/Rib9y9E.png" align="left" />
</a>

Cross browser testing and debugging provided by the very lovely team at BrowserStack.
