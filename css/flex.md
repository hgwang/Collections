# Flex的简要介绍和问题汇总
---

## 发展历程
- 老版本：2009年，`display: box || inline-box`
- 混合过度版本： 2011年，`display: flexbox || inline-flexbox`
- [最新标准版](https://www.w3.org/TR/css-flexbox-1/)：`display:flex || inline-flex`

## 容器属性
- flex-flow
  - flex-direction
  - flex-wrap
- justify-content
- align-items
- align-content

## 项目属性
- order
- flex
  - flex-grow
  - flex-shrink
  - flex-basis
- align-self

注意：**float,clear,vertical-align** 在伸缩项目上无效

## 兼容性
- [当前最新兼容性](http://caniuse.com/#feat=flexbox)
- autoprefixer

## 参考文章

- [阮一峰Flex布局教程](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)
- [W3C Flex标准](https://www.w3.org/TR/css-flexbox-1/)

## 各手机版本所出现的问题汇总[TODO]
