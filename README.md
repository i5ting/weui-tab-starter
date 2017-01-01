# 说明

## 将weui的example放到根目录

便于查阅

只需要修改example/index.js

```
    <link rel="stylesheet" href="/node_modules/weui/dist/style/weui.min.css"/>
```

## 使用browser-sync启动服务器

配置scripts

```
  "scripts": {
    "start": "./node_modules/.bin/browser-sync start --server",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
```

执行

```
$ npm start
```