# Welcome to realworld-koa-svelte 👋
![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000)
[![Documentation](https://img.shields.io/badge/documentation-yes-brightgreen.svg)](https://github.com/FanchGadjo/realworld-koa-svelte#readme)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/FanchGadjo/realworld-koa-svelte/graphs/commit-activity)
[![License: ISC](https://img.shields.io/github/license/FanchGadjo/realworld-koa-svelte)](https://github.com/FanchGadjo/realworld-koa-svelte/blob/master/LICENSE)
[![Twitter: FrancoisKerisit](https://img.shields.io/twitter/follow/FrancoisKerisit.svg?style=social)](https://twitter.com/FrancoisKerisit)

> Realworld app: fullstack svelte and koa

### 🏠 [Homepage](https://github.com/FanchGadjo/realworld-koa-svelte#readme)

## Description
This repo is a merge of two [RealWorld example apps](https://github.com/gothinkster/realworld) repos :
* frontend : [sveltejs/realworld](https://github.com/sveltejs/realworld)
* backend : [koa-knex-realworld-example](https://github.com/gothinkster/koa-knex-realworld-example)

## Install

```sh
npm install
```

### Install frontend

```sh
sudo apt install -y sqlite3
cd front
npm install
```

### Install backend
```sh
sudo apt install -y sqlite3
```

```sh
cd back
yarn run knex migrate:latest
yarn run knex seed:run
```

## Usage

### Usage frontend
```sh
cd front
npm run dev
```
### Usage backend
In another shell :
```sh
cd back
npm start
```

## Run tests

TODO

## Author

👤 **Francois KERISIT**

* Website: http://francoiskerisit.fr/
* Twitter: [@FrancoisKerisit](https://twitter.com/FrancoisKerisit)
* Github: [@FanchGadjo](https://github.com/FanchGadjo)
* LinkedIn: [@fkerisit](https://linkedin.com/in/fkerisit)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check [issues page](https://github.com/FanchGadjo/realworld-koa-svelte/issues). You can also take a look at the [contributing guide](https://github.com/FanchGadjo/realworld-koa-svelte/blob/master/CONTRIBUTING.md).

## Show your support

Give a ⭐️ if this project helped you!


## 📝 License

Copyright © 2020 [Francois KERISIT](https://github.com/FanchGadjo).

This project is [ISC](https://github.com/FanchGadjo/realworld-koa-svelte/blob/master/LICENSE) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
