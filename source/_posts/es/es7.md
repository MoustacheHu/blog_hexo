---
title: ES7基础知识点
date: 2020-11-28 17:02:44
comments: true
categories: 
    - web前端
    - ES
tags: ['ES7基础知识点']
---
### class的静态属性和实例属性
    1.静态属性
        使用“static”关键字声明（ES7后支持），静态属性属于类，静态方法中的this指向类本身；
        
        可以被子类继承或者被super调用，不可以被实例继承。
<!-- more -->
    2.实例属性
        属于实例对象，this指向实例对象。