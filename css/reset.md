# CSS 重置
---
## reset.css
相对「暴力」，不管有没有用，统统重置成一样的效果，且影响的范围很大，讲求跨浏览器的一致性。
## [neat.css](http://thx.github.io/cube/doc/neat)
基于normalize
- 解决Bug，特别是低级浏览器的常见Bug。
- 统一效果，但不盲目追求重置为0。
- 向后兼容。
- 考虑响应式。
- 考虑移动设备

## [normalize.css](https://github.com/necolas/normalize.css)
> A modern alternative to CSS resets

相对「平和」，注重通用的方案，重置掉该重置的样式，保留有用的 user agent 样式，同时进行一些 bug 的修复，这点是 reset 所缺乏的
