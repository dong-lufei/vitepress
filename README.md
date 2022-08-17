# 初次使用vitepress

## 选择或创建一个文件夹进去初始化
yarn init -y

## 安装2个开发依赖
yarn add -D vitepress vue

## 新建docs文件和相关markdown文件

## 配置package.json的scripts字段值
```json
"scripts": {
  "docs:dev": "vitepress dev docs",
  "docs:build": "vitepress build docs",
  "docs:serve": "vitepress serve docs"
}
```
## 启动项目