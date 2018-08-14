## Easycanvas

![https://github.com/chenzhuo1992/easycanvas/blob/master/demos/index.html](https://raw.githubusercontent.com/chenzhuo1992/easycanvas/master/demos/index_v2.gif)

Easycanvas是一个轻量、高效率的渐进式canvas渲染库。将canvas与一个树形的数据结构绑定，当数据改变时视图将随之更新，并且提供了一个Chrome插件来便于开发，包括数据结构的显示、对canvas中某个元素的样式进行调整等。并且提供了一些插件，支持物理引擎、3D模型渲染等扩展功能。支持微信小游戏。

- [中文教程及在线Demo](https://chenzhuo1992.github.io/easycanvas/).
- [相关：Easycanvas实现高仿热血传奇游戏](https://github.com/chenzhuo1992/Mir2/wiki/%E3%80%8AJS%E5%AE%9E%E7%8E%B0%E7%83%AD%E8%A1%80%E4%BC%A0%E5%A5%87%E3%80%8B1.%E5%BC%80%E5%8F%91%E5%89%8D%E7%9A%84%E5%87%86%E5%A4%87).
- [相关：Easycanvas实现3D版弹一弹小游戏](https://chenzhuo1992.github.io/tanyitan/).
- [English Guide(will update soon)](https://github.com/chenzhuo1992/easycanvas/blob/master/readme/build/readme.English.md).

#### Feature

- ☑ 渐进式基础库
- ☑ 2D渲染
- ☑ 精灵动画
- ☑ 物理引擎（插件）
- ☑ 事件、钩子
- ☑ 开发者工具（Chrome扩展插件）
- ☑ 基础文档
- ☑ 基础功能的单元测试
- ☑ 3D渲染（插件）
- ☑ 2D、3D混合渲染	
- ☑ 3000个150x150的图片2D渲染时保持60fps
- ☑ 1000个3D模型渲染时保持60fps
- ☑ 支持加载3ds模型（插件）
- ☑ 允许自定义组件
- ☑ 允许自定义插件
- ☑ 2D图片像素级编辑
- ☑ 文档补齐
- ☑ 支持加载mmd模型（插件）
- ☑ 支持加载dds图片（插件）
- ☑ 支持微信小游戏
- ☐ 更多功能的单元测试
- ☐ 调试工具的性能分析部分完善
- ☐ webgl的3D渲染性能优化

#### Changelog

- [Changelog](https://github.com/chenzhuo1992/easycanvas/blob/master/CHANGELOG.md).

### Introduction

A lite(30kb+) canvas library, includes a Chrome plugin for debugging. Support physics and animations with high performace. Suits mobile and PC(including IE).

### More demos

- `npm run dev`, then `localhost:8080/demos/demo1.html`.

### Chrome Plugin

Throw `./chrome-devtools/dist` to `Chrome://extensions`.

### How to use

#### Import Easycanvas:

- `build/easycanvas.js`: Node module.

- `build/easycanvas.standalone.dev.js`: Standalone version, support chrome develop tools.

- `build/easycanvas.standalone.prod.js`: Standalone version for production mode, 30kb+.
