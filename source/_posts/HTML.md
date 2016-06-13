---
title: [360前端星计划]前端开发基础课--HTML
toc: true
---

## 关于doctype

### doctype作用

- 文档类型声明

- 指定HTML页面使用的标准和版本

- 浏览器根据此决定使用哪种渲染模式

### 渲染模式

- 怪异模式 Quirks Mode   --不写doctype会进入怪异模式
- 准标准模式 Almost Standard Mode
- 标准模式 Standard Mode

## HTML5

### 设计思想

- 兼容已有内容

- 避免不必要的复杂性  e.g. doctype简化很多

- 解决现实的问题  e.g.有很多好用的API，真正解决开发者问题

- 优雅降级  e.g. 若浏览器不支持video，则解析标签内html语句

- 尊重事实标准

- 用户》开发者》浏览器厂商》标准制定者》理论完美

### 元数据元素

- base  指定基准URL及链接打开方式[默认页面打开方式]
- title 页面标题
- script 引入脚本
- style 嵌入页面样式表
- noscript 浏览器不支持脚本时才展示的内容
- meta 页面元数据 
  - ```<meta name = "keywords" content = "前端，HTML，CSS，JavaScript">```
  - ```<meta name = "description" content = "前端基础课程" >```
  - ```<meta name = ""```
  - ```viewport```
- link 引入外部资源 e.g.外联样式表

### a链接

- target


- href
  - mailto:  打开邮件客户端
  - tel: 打电话

### 引用

- <blockquote> 长引用
- <p>
- <cite> 短引用

列表

- 自定义列表dd dt
- 有序列表
- 无序列表

### 图片

- jpg 色彩丰富
- png 
  - 色彩较少时使用
  - png24可以半透明
- gif 无法半透明

### HTML公共属性

- id
- title 
  - 文字说明
  - 当内容显示不全时，可以将完整内容放到title里面
- lang
- style
- class
- 自定义 data-*
  - h5赋予新属性

## HTML5语义化

- HTML中的元素、属性及属性的值都拥有某些含义

- 开发者应该遵循语义来编写HTML

###语义化好处
- 可访问性
- 搜索引擎优化
- 易读
- 易维护


### 如何做到语义化

- 清楚了解每一个标签和属性的语义
- HTML中只描述内容和结构，样式留给CSS
- 手写HTML，避免使用生成工具
- 命名遵循行业通用标准
  - the hardest problem in programming: Naming things
  - microformats
    - hcard/vcard 给人的属性命名
    - h-product 给商品命名
    - h-
  - Schema.org  翻墙看一下
  - ARIA ```<div role = "button" aria-label = "Refresh"></div>```

## HTML如何学习

- 教程
  - webplatform.org的HTML教程
  - CodeCademy HTML & CSS
- 手册
  - HTML：The Living Standard
  - W3C





