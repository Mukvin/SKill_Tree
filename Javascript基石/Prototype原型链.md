
### 什么是原型链

对象。每个实例对象（ object ）都有一个私有属性（称之为 __proto__ ）指向它的构造函数的原型对象（prototype ）。该原型对象也有一个自己的原型对象( __proto__ ) ，层层向上直到一个对象的原型对象为 null。根据定义，null 没有原型，并作为这个原型链中的最后一个环节。  
[JavaScript深入之从原型到原型链](https://github.com/mqyqingfeng/blog/issues/2) .   
推荐： [ JavaScript原型链以及Object，Function之间的关系](https://segmentfault.com/a/1190000012553959)  

![img](http://zencode.in/imgs/2/1.jpg)
