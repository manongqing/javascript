---
js中window.onload和jqurey中$(function(){})的区别（面试题）
---

1.window.onload有且仅有一次，定义多次之后，后者覆盖前者，只会执行最后一个。
  
   而$(function(){})可以定义多次，按顺序执行。

2.window.onload是指当页面的所有资源加载完毕之后执行，比较慢。

   而$(function(){})是指当页面中的DOM元素加载完毕之后执行，比较快。

3.window.load不可简写。