#该项目是 YOJ 的前端，主要是使用 Vue3+Vue-CLI脚手架+Vuex状态管理+Arco Design组件库等实现同时还通过OpenAPI进行前端代码生成以及Markdown富文本编辑器等


# yoj-frontend

## 根据后台生成代码

```shell
openapi --input http://localhost:8121/api/v2/api-docs --output ./generated --client axios
```


## Project setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn serve
```

### Compiles and minifies for production

```
yarn build
```

### Lints and fixes files

```
yarn lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
