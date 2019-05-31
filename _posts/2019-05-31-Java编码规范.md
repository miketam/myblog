## 源文件

* 文件名是大小写敏感的
* 编码使用UTF-8
* 空白字符请使用空格
* 源文件结构：

```
    1. 版权声明
    2. package 语句
    3. import 语句
    4. class 定义
```

* package语句不能换行
* import语句
    * 无论是static还是其他导入都不要使用通配符导入形式
    * 不能换行
    * 先导入static block
    * 再导入非static block
    * 如果都有的话，那么static block和非static block之间增加一个空行
    * 不要static引入静态内部类
* class定义
    * 一个class文件中只有一个顶级类定义
    * class内容
        * 重载的方法不要分开
