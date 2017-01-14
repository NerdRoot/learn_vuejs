# Starting with vueJS

> A Vue.js project to learn

## Initial configuration

``` bash
# init new project
npm init

# install vue-cli to generate new template
npm i -D vue-cli

# add to package.json script {}
"script": {
  "vue": "vue"
}

# list available official templates
npm run vue
npm run vue -- list

# start new template from webpack

npm run vue -- init webpack-simple
```
## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).
