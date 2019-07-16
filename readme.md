## 函数式编程
### 纯函数 pure function
- 函数纯粹些 purity
- 无副作用 side effect mutation
```
return x+y 与
x+=y,return x 的区别
前者返回二者之和，不改变x的值
后者返回二者之和，但是改变x的值
```

### 引用透明性
    Referential Transparency 对于相同的输入，总是有相同的输出

- x.appender("xxx")，将xxx拼接到x后面并赋值给x，典型的违反引用透明性
