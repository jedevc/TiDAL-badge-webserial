# mdb-admin-template

> MDB Admin Dashboard

## Build Setup

``` bash
# install dependencies
yarn

# serve with hot reload at localhost:8080
yarn serve

# build for production with minification
yarn build

# build for production and view the bundle analyzer report
yarn build --report
```

## Docker

```bash
docker run --rm -t -v $PWD:/app -p 8080:8080 $(docker build -q .)
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
