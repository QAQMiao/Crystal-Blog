---
title: [360前端星计划]前端开发基础课--JavaScript
toc: true
---

## Coding Style

- 注释
- 缩进
- 命名
- 分号
- 空行

## Defensive 防御性编程

- 预防代码运行时因自己考虑不周出现问题

- 预防代码因别人影响而出现问题

- 方法

  - 加命名空间

  - 闭包

  - use strict

  - Object.defineProperty(对象，函数名，{

    value: fun,

    writable:false,

    enumable:false

    });

## Types

- judge Object.prototype.toString.call(argument) === "[object String]"

## Object、Json

- Object 
  - 属性的无序集合
  - 每个属性存放一个原始值、对象或函数
  - 深拷贝--mixin.js