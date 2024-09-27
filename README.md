# 這是一個記帳用的App
目前是透過firebase的 Hosting服務做後端部署，
另外也有使用到Authentication以及Realtime Database

透過google登入的方式建立帳號，並可以選擇創立群組或是加入現有的其他群組。
進入群組後目前有四個主要功能
* 消費紀錄（以月為基準逐項紀錄每筆消費）
* 消費分佈（以圖表與表格方式顯示該月份各類別消費金額）
* 債務結算（計算該群組內所有人互相的債務關係）
* 群組管理（群組創建人可以自行決定是否將其餘成員踢出）

也許未來還會新增其他功能

# accounting app (accounting-pwa)

A Accounting App

## Install the dependencies
```bash
yarn
# or
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```


### Lint the files
```bash
yarn lint
# or
npm run lint
```



### Build the app for production
```bash
quasar build
```

### Customize the configuration
See [Configuring quasar.config.js](https://v2.quasar.dev/quasar-cli-vite/quasar-config-js).
