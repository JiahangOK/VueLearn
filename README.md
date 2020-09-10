# VueLearn

The repository is used to learn Vue.js.

[TOC]

## Useful Links  
- Vue官方文档：https://cn.vuejs.org/index.html   
- Vue视频课程：https://www.bilibili.com/video/BV15741177

## 知识点  
- MVVM  
model+view model+view，双向绑定  
- 模板
- 插值操作
    - Mustache  
    {{}}
    - v-once  
    静态内容，不会随数据改变
    - v-html  
    展示html元素， 字符串里面有标签
    - v-text  
    {{}}等效
    - v-pre  
    设置不解析，比如让{{}}原封不动的显示出来
    - v-cloak  
    解析前有这个属性，解析后没有这个属性，经常和css配合使用
    - v-on  
    响应事件  
    语法糖：@ （语法糖就是个简写的形式）
- v-bind  
动态绑定属性，给属性赋值  
语法糖：:  
绑定class  
绑定style
- computed  
计算属性