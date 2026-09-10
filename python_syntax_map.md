# Python 语法必背知识地图

## 0. Python 基础认知

- Python 解释器
- Python 脚本
- Python 模块
- Python 包
- .py 文件
- `__name__`
- `__main__`
- Python 缩进规则
- Python 注释
- Python 多行语句
- Python 代码块
- Python 标识符
- Python 关键字
- Python 命名规范
- Python 动态类型
- Python 对象模型
- Python 变量与对象的关系
- 引用与对象
- 可变对象与不可变对象

## 1. 基本数据类型

### 1.1 数字

- int
- float
- complex
- 整数运算
- 浮点数运算
- `/`
- `//`
- `%`
- `**`
- 数字比较
- 数字类型转换
  - `int()`
  - `float()`
  - `complex()`

### 1.2 布尔值

- bool
- True
- False
- 布尔表达式
- 真值判断
- Truthy / Falsy

### 1.3 None

- None
- None 的判断
- `is None`
- `is not None`

### 1.4 字符串

- str
- 字符串创建
- 字符串索引
- 字符串切片
- 字符串拼接
- 字符串重复
- 字符串转义
- 原始字符串 `r""`
- 多行字符串
- 字符串不可变性
- 字符串常用方法
  - `split()`
  - `join()`
  - `strip()`
  - `replace()`
  - `find()`
  - `startswith()`
  - `endswith()`
  - `upper()`
  - `lower()`
  - `format()`
- f-string
- f-string 表达式
- 字符串格式化规则

## 2. 变量与赋值

- 变量定义
- 变量赋值
- 多变量赋值
- 链式赋值
- 解包赋值
- 交换变量
- 增量赋值
  - `+=`
  - `-=`
  - `*=`
  - `/=`
  - `//=`
  - `%=`
  - `**=`
- 变量删除 del
- 变量作用域
  - 局部变量
  - 全局变量
  - global
  - nonlocal

## 3. 运算符

- 算术运算符
- 比较运算符
- 赋值运算符
- 逻辑运算符
  - and
  - or
  - not
- 位运算符
  - `&`
  - `|`
  - `^`
  - `~`
  - `<<`
  - `>>`
- 成员运算符
  - in
  - not in
- 身份运算符
  - is
  - is not
- 运算符优先级
- 短路求值

## 4. 条件与控制流

### 4.1 条件判断

- if
- elif
- else
- 嵌套条件
- 条件表达式
- 三元表达式
- 多条件判断
- 条件链

### 4.2 循环

- for
- while
- for 遍历
- while 循环
- 嵌套循环
- break
- continue
- pass
- for-else
- while-else

## 5. List 列表

- list
- 列表创建
- 列表索引
- 列表切片
- 列表嵌套
- 列表修改
- 列表添加
- 列表删除
- 列表排序
- 列表反转
- 列表复制
- 列表拼接
- 列表常用方法
  - `append()`
  - `extend()`
  - `insert()`
  - `remove()`
  - `pop()`
  - `clear()`
  - `index()`
  - `count()`
  - `sort()`
  - `reverse()`
- 列表推导式
- 嵌套列表推导式
- 带条件的列表推导式

## 6. Tuple 元组

- tuple
- 元组创建
- 元组索引
- 元组切片
- 元组嵌套
- 元组解包
- 单元素元组
- 元组不可变性
- 元组与列表的区别
- 元组常用方法
  - `count()`
  - `index()`

## 7. Set 集合

- set
- 集合创建
- 集合元素特性
- 集合添加
- 集合删除
- 集合遍历
- 集合去重
- 并集
- 交集
- 差集
- 对称差集
- 子集
- 超集
- 集合推导式
- `add()`
- `remove()`
- `discard()`
- `pop()`
- `union()`
- `intersection()`
- `difference()`

## 8. Dict 字典

- dict
- 字典创建
- Key / Value
- 字典索引
- 字典修改
- 字典添加
- 字典删除
- 字典遍历
- Key 的要求
- 字典嵌套
- 字典解包
- 字典常用方法
  - `get()`
  - `keys()`
  - `values()`
  - `items()`
  - `update()`
  - `pop()`
  - `popitem()`
  - `setdefault()`
  - `fromkeys()`
- 字典推导式
- `**` 字典解包

## 9. 序列与切片

- Sequence 概念
- 索引
- 正向索引
- 负向索引
- 切片
  - start
  - stop
  - step
- 反向切片
- 切片赋值
- 可迭代对象
- `len()`
- `min()`
- `max()`
- `sum()`
- `sorted()`
- `reversed()`

## 10. 函数

### 10.1 函数基础

- 函数定义
- def
- 函数调用
- 参数
- 返回值
- return
- 无返回值函数
- 多返回值
- 返回 Tuple

### 10.2 参数

- 位置参数
- 关键字参数
- 默认参数
- 参数顺序
- 可变参数
- `*args`
- `**kwargs`
- Keyword-only 参数
- Positional-only 参数
- 参数解包
  - `*` 参数解包
  - `**` 参数解包

### 10.3 函数高级概念

- 函数是一等对象
- 函数赋值
- 函数作为参数
- 函数作为返回值
- 嵌套函数
- 闭包
- lambda
- 匿名函数
- 函数作用域
- LEGB 规则
- global
- nonlocal
- 函数注解
- 返回值注解
- Docstring
- `__doc__`

## 11. Lambda / 函数式编程

- lambda
- `map()`
- `filter()`
- `reduce()`
- `zip()`
- `enumerate()`
- `any()`
- `all()`
- `sorted(key=...)`
- `min(key=...)`
- `max(key=...)`
- 高阶函数
- 函数作为变量
- 函数作为参数
- 函数作为返回值

## 12. 推导式

- List Comprehension
- Set Comprehension
- Dict Comprehension
- Generator Expression
- 推导式条件
- 嵌套推导式
- 多层循环推导式
- 推导式中的函数调用

## 13. 类与对象

这是你必须重点掌握的一大块。

### 13.1 类基础

- 类的定义
- class
- 类对象
- 实例对象
- 类属性
- 实例属性
- 实例化
- 构造对象
- `__init__`
- self
- 实例方法
- 类方法
- 静态方法

### 13.2 类属性与实例属性

- 类属性
- 实例属性
- 属性查找
- 属性覆盖
- 类属性修改
- 实例属性修改
- `self.xxx`
- `Class.xxx`

### 13.3 方法

- 实例方法
- self
- `@classmethod`
- cls
- `@staticmethod`
- 静态方法
- 方法调用
- 方法绑定

### 13.4 构造与生命周期

- `__new__`
- `__init__`
- `__del__`
- 对象创建
- 对象初始化
- 对象销毁
- 对象生命周期

### 13.5 封装

- 公有属性
- `_xxx`
- `__xxx`
- 名称修饰 Name Mangling
- 私有属性
- `@property`
- Setter
- Getter
- property

### 13.6 继承

- 单继承
- 多继承
- 父类
- 子类
- 方法继承
- 属性继承
- 方法重写
- `super()`
- MRO
- Method Resolution Order
- `__mro__`

### 13.7 多态

- Duck Typing
- 方法重写
- 接口式设计
- 抽象基类
- ABC
- `@abstractmethod`

### 13.8 特殊方法

- Magic Methods
- Dunder Methods
- `__str__`
- `__repr__`
- `__len__`
- `__getitem__`
- `__setitem__`
- `__delitem__`
- `__contains__`
- `__iter__`
- `__next__`
- `__call__`
- `__eq__`
- `__lt__`
- `__hash__`
- `__enter__`
- `__exit__`

## 14. 异常处理

- Exception
- try
- except
- else
- finally
- 捕获异常
- 多异常捕获
- 异常类型
  - Exception
  - BaseException
- raise
- 主动抛出异常
- 自定义异常
- 异常继承
- 异常链
- raise from
- assert
- AssertionError

## 15. 模块与 import

- Module
- Package
- import
- from ... import
- import ... as
- from ... import ... as
- 模块搜索路径
- sys.path
- 相对导入
- 绝对导入
- `__init__.py`
- `__name__`
- `__main__`
- `if __name__ == "__main__"`
- 模块初始化
- 模块缓存
- sys.modules
- 循环 import
- `__all__`

## 16. 文件与 IO

- 文件对象
- `open()`
- 文件读取
- 文件写入
- 文件追加
- 文件关闭
- `with open()`
- 文本模式
- 二进制模式
- 编码
- encoding
- `read()`
- `readline()`
- `readlines()`
- `write()`
- `writelines()`
- 文件指针
- `seek()`
- `tell()`

## 17. Context Manager

- Context Manager
- with
- `__enter__`
- `__exit__`
- 上下文管理器协议
- contextlib
- contextmanager
- ExitStack

## 18. 迭代器

这一块对看懂项目代码非常重要。

- Iterable
- Iterator
- `iter()`
- `next()`
- `__iter__`
- `__next__`
- Iterator Protocol
- 可迭代对象
- 迭代器对象
- Iterable 与 Iterator 的区别
- 自定义迭代器
- 迭代器耗尽
- StopIteration

## 19. Generator 生成器

- Generator
- Generator Function
- yield
- yield from
- Generator Expression
- 生成器创建
- 生成器执行机制
- 生成器暂停
- 生成器恢复
- `send()`
- `throw()`
- `close()`
- StopIteration
- Generator 与 Iterator 的关系

## 20. 装饰器

- Decorator
- 函数装饰器
- `@decorator`
- 装饰器执行时机
- 装饰器包装函数
- 多层装饰器
- 带参数的装饰器
- 装饰器工厂
- 类装饰器
- functools.wraps
- 装饰器与闭包

## 21. 类型系统与 Type Hint

现代 Python 项目里非常重要。

- Type Hint
- 类型注解
- 变量类型注解
- 函数参数类型
- 返回值类型
- Optional
- Union
- Any
- None
- Literal
- Callable
- Type
- TypeVar
- Generic
- 泛型
- `list[int]`
- `dict[str, int]`
- `tuple[...]`
- `set[...]`
- `|` 类型联合
- typing
- typing_extensions
- Forward Reference
- 类型别名
- NewType
- Protocol

## 22. Dataclass

- dataclass
- `@dataclass`
- 字段定义
- 默认值
- `field()`
- default
- default_factory
- frozen
- slots
- `__post_init__`
- Dataclass 继承
- Dataclass 与普通 Class 的区别

## 23. Enum

- Enum
- IntEnum
- 枚举成员
- 枚举值
- 枚举遍历
- 枚举比较
- 枚举转换
- `auto()`

## 24. 常用内置函数

- `print()`
- `input()`
- `len()`
- `type()`
- `isinstance()`
- `issubclass()`
- `id()`
- `dir()`
- `help()`
- `vars()`
- `getattr()`
- `setattr()`
- `hasattr()`
- `delattr()`
- `callable()`
- `repr()`
- `str()`
- `format()`
- `range()`
- `enumerate()`
- `zip()`
- `map()`
- `filter()`
- `sorted()`
- `reversed()`
- `sum()`
- `any()`
- `all()`
- `abs()`
- `round()`
- `min()`
- `max()`
- `pow()`
- `hash()`

## 25. Python 对象模型

这是从"会写 Python"到"看懂复杂 Python"的关键。

- 一切皆对象
- Object
- Type
- Class
- Instance
- type
- object
- 对象身份
- 对象类型
- 对象值
- `id()`
- 引用
- 赋值与引用
- 浅拷贝
- 深拷贝
- copy
- `copy.copy()`
- `copy.deepcopy()`
- 可变对象
- 不可变对象
- 对象生命周期
- 引用计数
- 垃圾回收
- GC

## 26. Python 内存相关

- Reference
- Reference Counting
- Garbage Collection
- 循环引用
- GC
- gc 模块
- 对象生命周期
- 小整数缓存
- 字符串驻留
- is 与 ==
- 浅拷贝
- 深拷贝

## 27. 高级类机制

当你开始看大型 Python 项目，这些东西会逐渐出现。

- `__slots__`
- Descriptor
- Descriptor Protocol
- `__get__`
- `__set__`
- `__delete__`
- Property Descriptor
- Attribute Lookup
- `__getattribute__`
- `__getattr__`
- `__setattr__`
- `__delattr__`
- Metaclass
- type
- 自定义 Metaclass
- `__init_subclass__`
- `__new__`
- 类创建过程

## 28. 泛型与协议

- Generic
- TypeVar
- Generic Class
- Generic Function
- Protocol
- Structural Subtyping
- Duck Typing
- collections.abc
- Iterable
- Iterator
- Sequence
- Mapping
- Callable

## 29. Pattern Matching

现代 Python 代码可能出现。

- match
- case
- Pattern Matching
- Literal Pattern
- Variable Pattern
- Wildcard Pattern
- Sequence Pattern
- Mapping Pattern
- Class Pattern
- Guard
- case ... if

## 30. Async / Await

现代 Python 项目中非常重要。

- 异步编程
- async
- await
- Coroutine
- Coroutine Function
- Event Loop
- asyncio
- Task
- Future
- `asyncio.create_task()`
- `asyncio.gather()`
- Async Iterator
- Async Generator
- async for
- async with
- Async Context Manager
- `__aiter__`
- `__anext__`

## 31. 多线程 / 多进程

- Thread
- threading
- Thread 创建
- Thread 启动
- Thread 等待
- Lock
- RLock
- Condition
- Event
- Semaphore
- Queue
- Process
- multiprocessing
- Process Pool
- Thread Pool
- concurrent.futures
- ThreadPoolExecutor
- ProcessPoolExecutor
- GIL
- CPU-bound
- IO-bound

## 32. Python 并发模型

- 同步
- 异步
- 并发
- 并行
- Thread
- Process
- Coroutine
- Event Loop
- GIL
- IO 密集型
- CPU 密集型
- 线程安全
- 进程安全
- Race Condition
- Deadlock

## 33. 常用标准库

- 数据结构
  - collections
  - deque
  - Counter
  - defaultdict
  - OrderedDict
  - namedtuple
- 工具
  - itertools
  - functools
  - operator
- 系统
  - os
  - sys
  - pathlib
  - shutil
  - subprocess
  - platform
- 数据
  - json
  - csv
  - pickle
- 时间
  - time
  - datetime
  - timezone
- 正则
  - re
- 日志
  - logging
- 参数
  - argparse
- 配置
  - configparser

## 34. Python 包管理与环境

- Python Environment
- Virtual Environment
- venv
- pip
- pip install
- pip uninstall
- pip list
- pip freeze
- requirements.txt
- Package
- Wheel
- Source Distribution
- pyproject.toml
- setup.py
- setup.cfg
- Dependency
- Dependency Version
- Virtual Environment 隔离

## 35. Python 项目结构

- Python Package
- Module
- Package
- `__init__.py`
- `__main__.py`
- pyproject.toml
- src Layout
- Test Directory
- Configuration
- Entry Point
- CLI Entry Point
- Package Import
- Relative Import
- Absolute Import

## 36. 代码元编程 / 反射

这一部分不一定要最先学，但大型项目很容易碰到。

- Reflection
- Introspection
- `type()`
- `dir()`
- `vars()`
- `getattr()`
- `setattr()`
- `hasattr()`
- inspect
- `inspect.signature()`
- 动态创建对象
- 动态调用函数
- 动态导入
- importlib

## 37. Python 高级语法糖

- `@decorator`
- with
- async with
- async for
- yield
- yield from
- lambda
- `*args`
- `**kwargs`
- `*` 参数
- `**` 解包
- `:=` 海象运算符
- match/case
- 推导式
- Generator Expression
- f-string

## 38. Python 中最容易"看不懂"的语法

这一组建议你专门背：

- `*args`
- `**kwargs`
- `*list`
- `**dict`
- lambda
- `@decorator`
- yield
- yield from
- with
- as
- async
- await
- async for
- async with
- `__init__`
- `__new__`
- `__call__`
- `__iter__`
- `__next__`
- `__getitem__`
- `__getattr__`
- `__getattribute__`
- `__enter__`
- `__exit__`
- `super()`
- property
- classmethod
- staticmethod
- `@dataclass`
- match/case
- `:=`
- 类型注解
- Protocol
- Generic

## 39. 最终"必须掌握"的核心层

如果你的目的不是成为 Python 专家，而是尽快看懂新项目组的 Python 代码，我会把上面压缩成下面这几个核心层：

### 第一层：绝对基础

- 变量
- 数据类型
- 字符串
- List
- Tuple
- Dict
- Set
- 索引
- 切片
- 运算符
- if
- for
- while
- break
- continue

### 第二层：Python 日常语法

- 函数
- 参数
- 默认参数
- `*args`
- `**kwargs`
- return
- Lambda
- 推导式
- 解包
- enumerate
- zip
- map
- filter

### 第三层：面向对象

- Class
- Object
- Instance
- self
- `__init__`
- 属性
- 方法
- 类属性
- 实例属性
- classmethod
- staticmethod
- property
- 继承
- 多态
- super
- MRO
- Magic Method

### 第四层：大型项目必备

- Module
- Package
- Import
- `__init__.py`
- `__name__`
- Exception
- try/except/finally
- Context Manager
- with
- Iterator
- Generator
- Decorator
- Type Hint
- Dataclass

### 第五层：高级 Python

- Descriptor
- Metaclass
- `__getattribute__`
- `__getattr__`
- `__slots__`
- Reflection
- Async/Await
- Coroutine
- Event Loop
- Threading
- Multiprocessing
- GIL
- Generic
- Protocol
