# vue3 in vite

## 使用 vite 初始化 Vue3.0 项目`yarn create vite-app my-vue3`

## 配置 ts

安装 typescript

`yarn add typescript -D`
初始化 tsconfig.json
`npx tsc --init`

- 然后在控制台执行下面命令

npx tsc --init

## 配置 vue-router

`yarn add vue-router@4.0.0-beta7`

## 配置 vuex

`yarn add vuex@4.0.0-beta.4`

- 引入到 main.ts 中

```ts
import { createApp } from 'vue'
import App from './App.vue'
import './index.css'
import router from './router/index'
import store from './store/index'

const app = createApp(App)
app.use(router)
app.use(store)
app.mount('#app')
```

- 使用 Vue3.0 开发一个 TodoList 示例

> 10.13 项目启动失败
