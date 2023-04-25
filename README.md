# Vue2-Hello 课程介绍

一.掌握HTML、CSS、JavaScript、AJAX基础知识

二.选用VSCode作为课程中的开发工具

三.课程安排：Vue基础-》本地应用-》网络应用-》综合应用

## 一.Vue基础

①.JavaScript框架

②.简化Dom操作

③.响应式数据驱动

### 1.第一个Vue程序

1.导入开发版本的Vue.js

2.创建Vue示例对象，设置el属性合data属性

3.使用简洁的模板语法把数据渲染到页面上


### 2.el挂载点

①.Vue实例的作用范围是什么呢？
Vue会管理el选项命中的元素及其内部的后代元素

②.是否可以使用其他的选择器？
可以使用其他的选择器，但是建议使用ID选择器

③.是否可以设置其他的dom元素呢？
可以使用其他的双标签，不能使用HTML和BODY

### 3.data数据对象

1.Vue中用到的数据定义在data中

2.data中可以写复杂类型的数据

3.渲染复杂类型数据时，遵守js的语法即可

## 二.本地应用

①.通过Vue实现常见的网页效果

②.学习Vue指令，以案例巩固知识点

### 4.v-text指令

1.v-text指令的作用是：设置标签的内容（textContent）

2.默认写法会替换全部内容，使用差值表达式{{}}可以替换指示内容

### 5.v-html指令

1.v-html指令的作用是：设置元素的innerHTML

2.内容中有html结构会被解析成标签

3.v-text指令无论内容是什么，只会解析为文本

### 6.v-on指令基础

1.v-on指令的作用是：为元素绑定时间

2.事件名不需要写on

3.指令可以简写成@

4.绑定的方法定义在methods属性中

### 7.demo-计数器

1.创建Vue示例时：el(挂载点)，data(数据)，methods(方法)

2.v-on指令的作用是绑定事件，简写为@

3.方法中通过this关键字获取data中的数据

4.v-text指令的作用是：设置元素的文本值，简写为{{}}
