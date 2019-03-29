# createVue

本项目基于 webpack4 搭建 vue 项目。

[相关文章](https://blog.csdn.net/weixin_38788347/article/details/80882432)

你可以用此项目搭建属于你的项目！！

欢迎 star!

## 2018/11/14

-   添加 vue-router

-   添加 vuex

## 2018/12/29

-   添加 git-commit

1. `git add file`

2. `npm run commit`

3. `git push`

-   添加 axios

```js
// 使用方法,两者均为 promise

this.$ajax.get(url, data, config);

this.$ajax.post(url, data, config);
```

## 2019/03/29

加入 `copy-webpack-plugin` 插件，设置 static 静态资源文件夹，使其内容打包后存在于打包后的 static 文件夹中
