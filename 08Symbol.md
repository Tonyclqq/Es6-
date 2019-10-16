# 数据类型Symbol

**Symbol**是一个新的基本数据类型，而且是一个值类型的

使用 Symbol函数执行得到一个Symbol数据类型

```javascript
let  sym1 =  Symbol();
console.log(typeof sym1);
```

`作用` 跟字符串差不多，但是使用Symbol函数得到一个数据 每一个是完全不同的 

Symbol可以接受一个参数()是对这个Symbol数据的描述

即使描述一样，但是值也是不相同的

Symbol有什么用？-->

1.一般当做对象的属性

2.Symbol值不可以跟其他值计算

3..Symbol值不可以转为数字

4.Symbol可以转布尔值

5.可以toString变成显示字符串

6.Symbol.for()找到相同参数的Symblo的值，找到这个值返回，如果没有就创建一个新的Symbol的值

```javascript
let zf2 = Symbol.for("zhufeng");
let zf3 = Symbol.for("zhufeng");
console.log(zf3 == zf2);
```



