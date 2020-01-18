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

---

This project was generated with [electron-vue](https://github.com/SimulatedGREG/electron-vue)@[45a3e22](https://github.com/SimulatedGREG/electron-vue/tree/45a3e224e7bb8fc71909021ccfdcfec0f461f634) using [vue-cli](https://github.com/vuejs/vue-cli). Documentation about the original structure can be found [here](https://simulatedgreg.gitbooks.io/electron-vue/content/index.html).
