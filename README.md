# PythonStudy

## 学习 Python 的笔记

### 01 入门

主要内容：输入输出字符串

- `print()`输出控制
- 变量：
  - 变量赋值；
  - 变量值互换（一句）
- 字符串：
  - 单、双、三引号用法
  - 转义符“\”用法（转义、行末未完待续）
  - 原始字符串“r”
  - 长字符串
  - 字符串加乘法

### 02 基础函数

- 函数`input()`
- 模块`random`
  - `random.randint(x,y)`
  - 随机数重现
    - `random.getstate()`
    - `random.setstate()`
- 小程序示例：应用 分支语法，比较运算符，算数运算符，循环语法，嵌套，random 模块
- 数值类型
  - 整型
  - 浮点型
    - 模块`decimal`：十进制定点和浮点运算，解决浮点型精度问题
  - 复数
- 数值计算
  - 数值计算的类型
    - 运算符`+`,`-`,`*`,`/`,`//`,`%`,`-x`,`+x`,`**`
    - 运算函数`divmod()`,`abs()`,`pow()`,`c.conjugate()`
    - 类型转换函数`int()`,`str()`,`float()`,`complex()`
- 布尔类型
  - `Bool()`：返回布尔值`T`or`F`
    - `Bool()`返回`False`的情况
  - 逻辑运算符（布尔运算）
    - `and`,`or`,`not`
    - `True` = 1, `False` = 0
    - `and`和`or`运算
      - 操作数
      - **短路逻辑**
- 运算符优先级

## 03 分支与循环

一定要有“：”

- 分支结构
  - `if`语句
    - 5 种结构（含 1 种条件表达式）
  - 分支结构的嵌套
  - `assert`关键字（断言）
- 循环结构
  - `while`循环
  - `for`循环
    - 变量循环体内计算值不影响再进入循环条件值
    - 序列不止为数值
  - `range()`函数
  - `break`语句
  - `continue`语句

## 04 列表

“.”为作用域

- 列表创建
- 插入元素
  - `append()`方法
    - 接受一个参数
  - `extend()`方法
    - 接受一个参数（列表）
  - `insert()`方法
    - 支持插入一个参数
    - 列表为空时，位置参数无效
- 获取列表元素（`list[]`）
  - 获取列表中的列表元素（`list[][]`）
- 替换列表元素
- 删除列表元素
  - `remove()`方法
  - `del()`语句
  - `pop()`方法
- 列表分片
- 列表常用操作符
  - 比较操作符
  - 逻辑操作符
  - 连接操作符
  - 重复操作符
  - 成员关系操作符
