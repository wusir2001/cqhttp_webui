# CQHTTP WebUI

> 以 https://github.com/richardchien/coolq-http-api/ 为后端的WeUI

## 效果展示
![pic_1](https://github.com/ma6254/cqhttp_webui/raw/master/src/assets/a1.gif)

## Demo
> Demo页面的托管和Pages服务由coding.net支持
> Demo页面可能会有css未加载以及跟发布版本不统一的问题, 推荐自行build

[点击这里](http://sand12.coding.me/cqhttp_webui_demo/)

## docker-compose
```bash
# start a cqhttp
docker-compose up -d

# stop a cqhttp
docker-compose down
```

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
