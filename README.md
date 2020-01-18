# electron_vue_app

[nodejs v10.18.1](https://nodejs.org/download/release/v10.18.1/)

> com.electron.vue.app1

**Powser shell**
```bash
cnpm install vue-cli
vue init simulatedgreg/electron-vue electron_vue_app  

cnpm install  

npm run dev  
cnpm run dev  
yarn run dev
```

Package.json:
```xml
"build":{
    "electronDownload": {
      "mirror": "https://npm.taobao.org/mirrors/electron/"
    }
}
```

build exe
```shell
npm run build
```

**See also:**
#### Office Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:9080
npm run dev

# build electron application for production
npm run build

# run unit & end-to-end tests
npm test


# lint all JS/Vue component files in `src/`
npm run lint

```
