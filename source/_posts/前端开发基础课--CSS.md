---
title: [360前端星计划]前端开发基础课--CSS
toc: true
---


## 字体系列

- serif衬线体
  - Georgia
  - 宋体
- Sans-Serif无衬线体
  - Arial
  - Helvetica
  - 黑体
  - 微软雅黑
- Monospace等宽字体
  - Consolas
  - Courier
  - 宋体
- 不能把中文字体放在英文字体前面

## font-size

- 字体大小可用px，百分比，em
- 初始值为medium，一般为16px

### em

- 一般是相对于font-size的计算值
  - 2em -> 看元素当前的font-size，然后乘以2，赋给当前属性
- 用在font-size上时，是相对于父元素的font-size来算的

### line-height

- 段落文字一般取1.4~1.8
- 可使用px，数字，em做单位
- 当父元素使用```line-height:1.5```时，相当于子元素中写```line-height：1.5em```

### HSL和HSLA

- Hue:色相，是色彩的基本属性，取值范围是0-360
- Suturation:饱和度
- Lighting:亮度
- piknik & colorrrs & JS Bin

# CSS进阶

## 盒模型

### width

- 指定content box宽度
- 百分数相对于父容器（包含块）的content box宽度

### height

- 指定content box高度
- 百分数相对于父容器（包含块）的content box高度
- 只有当包含块的高度不依赖该元素时，百分比高度才生效！！！（所以之前设置的100%都不生效，就是因为没有设置html高度）

tips：可以通过width和height为0，然后设置某个边的border来做出一个三角形

### boxing-sizing

- border-box 此时设置的高度宽度，为border盒子的宽度和高度。更加合理。

### 浮动

- 浮动不会影响后面的块级框
- 行内元素会受到浮动影响，会避开浮动元素

### 清除浮动

- clear
  - Generated Content    ------::before ::after
- BFC
  - 在BFC中，框会从包含块的顶部开始，从上到下摆放
  - BFC内的浮动
  - BFC不会和浮动元素重叠
- BFC的创建
  - 浮动框
  - 绝对定位框
  - 非块级的块容器
  - overflow属性为非visible的值
- BFC作用
  - 清除浮动
  - 防止margin折叠
  - 两栏布局

    ​

