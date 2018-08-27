# JavaScript-Component-Tab

## 组件功能
使用面向对象方式封装 Tab功能组件

## 组件实现方式
把初始化的代码封装到一起，绑定事件的代码封装到一起，都作为方法绑定到原型上
```JavaScript
function Tab(e){
  this.e = e;
  this.init()
  this.bind()
}

Tab.prototype.init = function(){
  //初始化
}

Tab.prototype.bind = function(){
  //事件
}
```

## 如何使用
直接 new Tab 即创建一个新对象即可。后面使用原生JavaScript选择DOM的方法选择到该 tab 的 class
```JavaScript
var tab1 = new Tab(document.querySelectorAll('.tab')[0])
```
