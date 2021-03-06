# Dogband

## Test pages

* [Mainpage](https://mentikora.github.io/dogband/dist/index.html)
* [Filter](https://mentikora.github.io/dogband/dist/home-filter.html)
* [Lost-found](https://mentikora.github.io/dogband/dist/lost-found.html)
* [My-pets](https://mentikora.github.io/dogband/dist/my-pets.html)
* [User-page](https://mentikora.github.io/dogband/dist/user-page.html)
* [User-header](https://mentikora.github.io/dogband/dist/user-header.html)

## Installation
```
npm install
```
## Start Dev Server
```
npm run dev
```

## Build Prod Version
```
npm run build
```

### Features:

* ES6 Support via [babel-loader](https://github.com/babel/babel-loader)
* SASS Support via [sass-loader](https://github.com/jtangelder/sass-loader)
* Linting via [eslint-loader](https://github.com/MoOx/eslint-loader)
* Hot Module Replacement

When you run `npm run build` we use the [extract-text-webpack-plugin](https://github.com/webpack/extract-text-webpack-plugin) to move the css to a separate file and included in the head of your `index.html`, so that the styles are applied before any javascript gets loaded. We disabled this function for the dev version, because the loader doesn't support hot module replacement.

Link source: 
```
https://github.com/wbkd/yet-another-webpack-es6-starterkit
```
