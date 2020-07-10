#   作用域是什么？

-   react MVVM setState state 状态机制
     js 变量就是程序的状态  声明空间（ 闭包， 作用域， 变量查找， 变量提升 ）  存储值
     值可以被修改
-   赋值过程
    var a = 2; 它是怎么运行的？
    var 关键字 a identifier 标识符 = 运算符 2 value literal
    1.  高级语言 CPU 无法理解并且无法执行
    2.  
## 编译原理
语言执行的底层
操作系统 -> 编译原理
引擎  V8 编译器 解释器
1.  分词/词法分析阶段 [var, a, =, 2]
    token(词法单元) 检查语法错误
2.  语法分析阶段
    抽象语法树 （AST： Abstrac Syntax Tree）
    一切的程序都是 数据结构 + 算法
    编译器也是需要运行的
    eg: HTML <div></div> DOM树
3.  代码生成

最后将高级语言转换成机器可执行的二进制文件

    即时编译器(JIT)
    JS 运行时编译 
    JAVA C++ 预编译
    编译器（Compiler）
    解释器（Interpreter）