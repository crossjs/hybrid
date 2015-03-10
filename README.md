# hybrid
hybrid development toc

- 基础篇（2015/03/12）
  - HTML/CSS/JS 基本概念及相关框架/库讲解
- 开发篇（2015/03/12）
  - 模块化、组件化、模块化、自动化开发简介
- 应用篇（2015/03/12）
  - 应用工厂 Module 开发及 UI 框架使用介绍

## 基础篇

> HTML/CSS/JS 基本概念及相关框架/库讲解

### HTML

> 包含 Data 与 Layout，通过浏览器渲染成 DOM Tree

- HTML
- HTML5

### CSS

> 设置 DOM Tree 各元素样式

- css
- less/scss

### JS

> 获取 DOM 节点，管理 DOM 属性，侦听 DOM 事件（配图）

- coffee
- typescript

### JS/UI 框架/库

> 有面向 DOM 的，面向 GUI 的，以及基于 MV* 的。

- [jQuery](http://jquery.com)
- [Zepto.js](http://zeptojs.com)
- [AngularJS](https://angularjs.org)
- [Bootstrap](http://getbootstrap.com/)
- [React](http://facebook.github.io/react/)
- [AraleJS](https://github.com/aralejs)
- [**Sencha Touch**](https://www.sencha.com/products/touch/)
- [**jQuery Mobile**](http://jquerymobile.com/)

## 开发篇

> 模块化、组件化、模板化、自动化开发简介

### 前端开发

- 以前很简单：需求简单 + 语言实现简单
- 现在很复杂：需求复杂 + 语言实现简单

### 模块化

> 在代码文件方面，提高复用率及可维护性

- [**SeaJS**](http://seajs.org/)
- [RequireJS](http://requirejs.org/)
- [ES6](http://es6.ruanyifeng.com/)

### 组件化

> 在用户需求方面，提高复用率及可维护性

- [WebComponents](https://github.com/webcomponents)
- [Polymer](https://github.com/polymer)
- [React](http://facebook.github.io/react/)
- [**AraleJS**](https://github.com/aralejs)

### 模板化

> 基于 JS 的模板引擎，数据与结构分离，提高 UI 呈现灵活性

- [**Handlebars**](http://handlebarsjs.com/)
- [mustache](https://mustache.github.io/)
- [doT.js](http://olado.github.io/doT/)

### 自动化

> 让机器代替人工。

- [**node**](http://nodejs.org/)
- [**grunt**](http://gruntjs.com/)
- [gulp](http://gulpjs.com/)
- [**jshint**](http://jshint.com/)
- [QUnit](http://qunitjs.com/)
- [**mocha**](http://mochajs.org/)
- [Jasmine](http://jasmine.github.io/)

## 应用篇

> 应用工厂 Module 开发的思考与 UI 框架使用介绍

### Module 开发

- 样式如何统一？
    - 一个页面里的两个模块，应该基于同一个 CSS Reset
- 依赖库如何统一管理？
    - 场景1：一个页面里的两个模块，分别依赖 jQuery 1.11.2 和 2.1.3
    - 场景2：一个页面里的两个模块，都依赖同一个版本的 jQuery
- 打包问题？

### UI 框架

- [jQuery Mobile]()
- [Origami](http://origami.ft.com/)
