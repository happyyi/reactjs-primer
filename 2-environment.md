# react开发环境的搭建
可以从官方网站直接下载
[react各版本下载地址](https://github.com/facebook/react/releases)

react解压之后的源码文件夹包括：
![react文件](https://segmentfault.com/img/bVHDkW?w=899&h=300)

每个文件夹的作用：
* react.js 核心代码，必须
* react-dom.js Dom渲染
* react-dom-fiber.js 虚拟调用栈，做任务调度的
* react-dom-server.js Dom服务器端渲染
* react-with-addons.js 拓展功能

## 注意区分一下IDE和文本编辑器 ##
ide是针对那些需要编译的的语言的，不需要编译的解释型语言，没有所谓的ide

需要的sublime text3的插件
1. emmet(依赖一个python v8引擎)
2. Html-Css-JsPrettify（格式化的工具，需要依赖nodejs）
3. spacegray是一个主题（让代码更加好看，可以提升开发效率）

react兼容ie8及以上版本

react页面本质上是一个包含了css和js【jsx】的html代码

路径只是：./表示当前路径 ../表示上一级路径
react实际代码需要写成type=text/jsx

* render函数是把js转换成html
* React.render(jsxcode,renderTarget)