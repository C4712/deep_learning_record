## 1.安装docsify记录

1. 安装nodejs

```python
去官网下载nodejs安装即可https://nodejs.org/zh-cn/
查看安装成功指令 “node -v” nodejs 版本和 “npm -v” npm 版本
```

2. 安装docsify
```python
在cmd窗口输入：npm install docsify-cli -g
```
3. 初始化第一个docsify项目

```python
初始化：docsify init ./docs
运行本地服务：docsify serve ./docs
可通过显示的浏览器访问，对应的md文件为显示的文件内容
```
## 2. 第一次使用

配置body部分,coverpage: true(不设置为true有时候会报错)

```python
<body>
  <div id="app"></div>
  <script>
    window.$docsify = {
      name: '深度学习-记录',
      loadSidebar: true,
      subMaxLevel: 3,
      auto2top: true,
      alias: {
        '/.*/_sidebar.md': '/_sidebar.md'
      },
      coverpage: true,
      repo: '',
    }
  </script>
```
## 3. 使用语法

```python
-sidebar.md :对应左侧目录结构，设置后可以将其固定成_didebar希望的目录结构
目录点击跳转实例[显示内容](跳转文件)：[1.2 常用软件安装 ](./电脑基础/docsify安装.md)  当是三级目录是会报错
默认显示README.md对应文件内容。
```
```python

```
