# gulp-boilerplate

## Install

```shell
$ cd gulp-boilerplate
$ yarn install
```

## Run locally

Start dev server.

```shell
$ yarn dev
```

## Build

Builds the project for production to the dist folder.

```shell
$ yarn build
```

## Deploy

Deploy to gh-pages
```shell
$ cd gulp-boilerplate 
$ rm -rf node_modules/gulp-gh-pages/node_modules/gift
$ cp -rf node_modules/gift node_modules/gulp-gh-pages/node_modules
```
```shell
$ yarn deploy
```
