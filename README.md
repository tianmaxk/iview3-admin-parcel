# iview3-admin-parcel
仿造IView官方admin demo，基于Parcel构建

> 使用说明

```bash
请使用Node版本 >= 9.10
```

```bash
$ npm install xserver-cli -g

$ x-cli parcel-vue myproject
```

> 开发调试
```bash
$ npm run dev
```

> 正式构建
```bash
$ npm run build
```

>目录结构
```js
├── dist                构建结果
├── index.html          首页文件
├── node_modules
├── package.json
├── src                 开发源码
│   ├── App.vue			单页组件入口
│   ├── assets			需要编译构建的静态资源
│   ├── components		组件集合
│   ├── main.js			入口JS
│   └── router			路由控制
└── static              静态文件
    ├── css
    ├── img
    └── js
```
