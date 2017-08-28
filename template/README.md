# {{ name }}

> {{ description }}

## Build Setup

``` bash
# install dependencies
npm install

# 引入 24好玩 内部库
#   - 前提: 项目必须是 Git 库
# 基础库
npm run lib-base
# IO 层级的库
npm run lib-store

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run deploy

# build for production and view the bundle analyzer report
npm run deploy --report
{{#unit}}

# run unit tests
npm run unit
{{/unit}}
{{#e2e}}

# run e2e tests
npm run e2e
{{/e2e}}
{{#if_or unit e2e}}

# run all tests
npm test
{{/if_or}}
```


For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
