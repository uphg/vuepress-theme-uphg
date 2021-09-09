# Vuepress theme uphg

自定义的一个 Vuepress 主题，添加了自定义的滚动条和目录组件。

## 安装

```sh
yarn add vuepress-theme-uphg
# or npm i vuepress-theme-uphg
```

## 使用

在 `.vuepress/config.js` 中添加以下内容

```js
module.exports = {
  theme: 'vuepress-theme-xx'
}
```

## 插件

默认自带了以下插件，不可关闭。

- [@vuepress/plugin-active-header-links](https://github.com/vuejs/vuepress/tree/master/packages/@vuepress/plugin-active-header-links)
- [@vuepress/plugin-google-analytics](https://github.com/vuejs/vuepress/tree/master/packages/%40vuepress/plugin-google-analytics)
- [@vuepress/plugin-search](https://github.com/vuejs/vuepress/tree/master/packages/%40vuepress/plugin-search)
