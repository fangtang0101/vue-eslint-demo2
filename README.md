# vue-eslint-demo1

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


### 说明
此项目 仅仅 只是 用 @vue-cli 创建的不带 eslit 的最初始的项目，演示了 vue 项目 只单独集成 prettier，并在vscode 中配合插件 prettier-code-format 使用
1. 添加 .prettierrc 文件（如果不加，那么就使用插件默认的）
2. 安装插件 prettier-code-format
3. code-首选项-设置 搜索 prettier 即可看到 插件的默认配置
4. 找到 setting 文件 增加 "eslint.autoFixOnSave": true
