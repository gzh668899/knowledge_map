# Python 完整知识体系地图

## 00. Python 基础语法

- Python 程序结构
- 注释
- 缩进
- 标识符
- 关键字
- 变量
- 常量
- 字面量
- 表达式
- 语句
- 代码块
- 多行语句

## 01. 基本数据类型

- None
- bool
- int
- float
- complex
- str
- bytes
- bytearray
- memoryview

## 02. 数字

- 整数
- 浮点数
- 复数
- 数值运算
- 整除
- 取模
- 幂运算
- 位运算
- 数值比较
- int 转换
- float 转换
- decimal / fractions

## 03. 字符串

- 字符串创建
- 字符串索引
- 字符串切片
- 字符串拼接
- 字符串重复
- 字符串遍历
- 字符串比较
- 字符串查找
- 字符串替换
- 字符串分割
- 字符串连接
- 大小写转换
- 去除空白
- startswith / endswith

### 字符串格式化

- %
- str.format()
- f-string

- 原始字符串
- 多行字符串
- 转义字符
- Unicode
- encode
- decode

## 04. 列表 list

- 创建
- 索引
- 切片
- 遍历

### 添加元素

- append
- extend
- insert

### 删除元素

- remove
- pop
- clear
- del

- 修改元素

### 排序

- sort
- sorted

- 反转
- 查找
- count
- index
- 列表复制
- 浅拷贝
- 列表推导式

## 05. 元组 tuple

- 创建
- 单元素 tuple
- 索引
- 切片
- 遍历
- 解包
- 嵌套 tuple
- tuple 与 list
- 不可变性

## 06. 字典 dict

- 创建
- key / value
- 索引访问
- get
- 添加
- 修改
- 删除
- pop
- popitem
- clear
- keys
- values
- items
- update
- setdefault
- 遍历
- 字典推导式
- 嵌套字典
- 字典解包

## 07. 集合 set

- 创建
- 添加
- 删除
- 遍历
- 成员判断
- 并集
- 交集
- 差集
- 对称差集
- 子集
- 超集
- frozenset
- 集合推导式

## 08. 序列与可迭代对象

- sequence
- iterable
- iterator
- index
- slice
- len
- in
- reversed
- enumerate
- zip
- unpacking

## 09. 条件与流程控制

- if
- elif
- else
- 条件表达式
- match / case
- for
- while
- break
- continue
- pass
- else with loop

## 10. 运算符

- 算术运算符
- 比较运算符
- 逻辑运算符
- 位运算符
- 赋值运算符
- 增量赋值
- 成员运算符
- 身份运算符
- is
- is not
- in
- not in
- := 海象运算符
- 运算符优先级

## 11. 函数

- 函数定义
- 函数调用

### 参数

- 位置参数
- 关键字参数
- 默认参数
- 可变参数
- *args
- **kwargs
- 仅位置参数
- 仅关键字参数

- 返回值
- 多返回值
- return
- 参数解包
- 函数注解
- 函数对象
- 函数作为参数
- 函数作为返回值
- first-class function

## 12. 作用域与命名空间

- 局部作用域
- 全局作用域
- enclosing 作用域
- built-in 作用域
- LEGB
- global
- nonlocal
- namespace
- globals()
- locals()

## 13. 推导式

- 列表推导式
- 字典推导式
- 集合推导式
- 条件推导
- 嵌套推导
- 推导式作用域

## 14. Lambda

- lambda 基础
- lambda 参数
- lambda 返回值
- lambda 表达式
- lambda 与 sorted
- lambda 与 map
- lambda 与 filter
- lambda 与闭包

## 15. 闭包

- nested function
- 自由变量
- enclosing scope
- 闭包形成
- 闭包变量
- nonlocal
- 闭包应用

## 16. 装饰器

- decorator 基础
- 函数装饰器
- 多层装饰器
- 装饰器参数
- 带参数装饰器
- 类装饰器
- functools.wraps
- 装饰器执行顺序

## 17. 类与对象

- class
- object
- 实例
- 类属性
- 实例属性
- 实例方法
- 类方法
- 静态方法
- self
- cls
- __init__
- __new__
- __del__
- 属性访问
- 方法调用
- 类对象本身

## 18. 面向对象

- 封装
- 继承
- 单继承
- 多继承
- 方法重写
- 多态
- super
- isinstance
- issubclass
- MRO
- C3 linearization
- mixin

## 19. 属性与访问控制

- public
- _name
- __name
- name mangling
- @property
- property getter
- property setter
- property deleter
- descriptor

## 20. 特殊方法 / 魔术方法

- __init__
- __new__
- __del__
- __str__
- __repr__
- __format__
- __bytes__
- __len__
- __bool__
- __getitem__
- __setitem__
- __delitem__
- __contains__
- __iter__
- __next__
- __call__
- __enter__
- __exit__
- __eq__
- __lt__
- __le__
- __gt__
- __ge__
- __add__
- __sub__
- __mul__
- __truediv__
- __hash__
- __getattr__ / __getattribute__

## 21. 模块

- module
- import
- from import
- import as
- 模块搜索
- __name__
- __main__
- __file__
- __all__
- 模块缓存
- 循环导入

## 22. 包

- package
- 子包
- __init__.py
- 相对导入
- 绝对导入
- 包结构
- namespace package

## 23. 异常处理

- exception
- raise
- try
- except
- else
- finally
- 多异常捕获
- 异常链
- from
- 自定义异常
- BaseException
- Exception
- traceback
- 异常传播

## 24. 文件与 IO

- open
- 文件模式
- read
- readline
- readlines
- write
- writelines
- seek
- tell
- flush
- close
- with
- 上下文管理器
- 文本 / 二进制 IO

## 25. 迭代器

- iterable
- iterator
- iter()
- next()
- __iter__
- __next__
- 自定义迭代器
- StopIteration

## 26. 生成器

- generator
- yield
- yield from
- next
- send
- throw
- close
- Generator
- 生成器表达式
- 惰性求值

## 27. 上下文管理器

- with
- __enter__
- __exit__
- contextmanager
- ContextDecorator
- 多上下文管理器
- 异常处理

## 28. 类型注解

- 变量类型注解
- 函数参数注解
- 返回值注解
- Optional
- Union
- Any
- Literal
- Callable
- Type
- TypeVar
- Generic
- Protocol
- TypedDict
- Final
- ClassVar
- Self
- Annotated
- 类型别名

## 29. dataclass

- @dataclass
- 字段
- 默认值
- default_factory
- field
- frozen
- order
- slots
- post_init
- dataclass inheritance

## 30. 枚举

- Enum
- IntEnum
- StrEnum
- Flag
- auto
- value
- name
- 枚举遍历

## 31. 泛型编程

- TypeVar
- Generic
- 泛型函数
- 泛型类
- 泛型约束
- Protocol
- structural typing
- 类型参数

## 32. 函数式编程

- map
- filter
- reduce
- zip
- enumerate
- any
- all
- min
- max
- sum
- sorted
- operator

## 33. functools

- partial
- partialmethod
- wraps
- reduce
- lru_cache
- cache
- cached_property
- singledispatch
- update_wrapper

## 34. itertools

- count
- cycle
- repeat
- chain
- compress
- dropwhile
- takewhile
- filterfalse
- islice
- accumulate
- product
- permutations
- combinations

## 35. collections

- Counter
- defaultdict
- deque
- namedtuple
- OrderedDict
- ChainMap
- UserDict / UserList / UserString

## 36. 正则表达式

- re
- compile
- match
- search
- findall
- finditer
- split
- sub
- groups
- group
- 贪婪匹配
- 非贪婪匹配
- 捕获组
- 命名组
- lookahead / lookbehind

## 37. 日期与时间

- datetime
- date
- time
- timedelta
- timezone
- strftime
- strptime
- 时间戳
- 时区

## 38. JSON / 数据序列化

- json
- dumps
- loads
- dump
- load
- JSONEncoder
- JSONDecoder
- pickle
- 序列化 / 反序列化

## 39. 操作系统相关标准库

- os
- sys
- pathlib
- shutil
- glob
- tempfile
- subprocess
- signal
- platform

## 40. 日志

- logging
- Logger
- Handler
- Formatter
- Filter
- LogLevel
- basicConfig
- logging hierarchy
- logging configuration

## 41. 命令行参数

- sys.argv
- argparse
- ArgumentParser
- positional argument
- optional argument
- subcommand
- type
- choices
- help

## 42. 测试

- unittest
- TestCase
- assert
- setUp
- tearDown
- mock
- patch
- doctest

## 43. 并发与并行

- threading
- Thread
- Lock
- RLock
- Condition
- Event
- Semaphore
- multiprocessing
- Process
- Queue
- Pipe
- Pool

### concurrent.futures

- ThreadPoolExecutor
- ProcessPoolExecutor

- GIL

## 44. 异步编程

- async
- await
- coroutine
- asyncio
- event loop
- Task
- Future
- create_task
- gather
- wait
- sleep
- async for
- async with
- async generator

## 45. 反射

- getattr
- setattr
- hasattr
- delattr
- dir
- vars
- callable
- isinstance
- issubclass
- inspect

## 46. 描述符

- descriptor
- __get__
- __set__
- __delete__
- data descriptor
- non-data descriptor
- property
- method descriptor
- descriptor lookup

## 47. 元类

- type
- metaclass
- __metaclass__
- __new__
- __init__
- __prepare__
- 动态创建类
- 元类继承
- metaclass conflict

## 48. Python 对象模型

- 一切皆对象
- object
- type
- 类也是对象
- 实例也是对象
- 对象身份
- 对象类型
- 对象值
- id
- type
- 引用
- 对象属性

## 49. Python 内存管理

- 引用
- 引用计数
- 垃圾回收
- gc
- 循环引用
- weakref
- 对象生命周期
- 对象创建
- 对象销毁
- 内存分配

## 50. Python 字节码

- bytecode
- code object
- dis
- opcode
- frame
- stack
- 字节码执行

## 51. Python 执行模型

- 源代码
- AST
- 编译
- bytecode
- code object
- frame
- execution
- interpreter

## 52. AST

- ast
- parse
- AST Node
- NodeVisitor
- NodeTransformer
- AST 遍历
- AST 修改
- AST 编译

## 53. 动态特性

- 动态类型
- 动态绑定
- 动态属性
- 动态创建对象
- 动态创建类
- eval
- exec
- globals
- locals

## 54. Python 包管理

- package
- module
- pip
- requirements
- pyproject.toml
- wheel
- source distribution
- virtual environment
- venv

## 55. Python 高级语法

- unpacking
- extended unpacking
- starred expression
- assignment expression
- structural pattern matching
- positional-only parameter
- keyword-only parameter
- positional-only argument
- walrus operator
- f-string advanced syntax

## 56. Python 高级函数机制

- first-class function
- higher-order function
- closure
- decorator
- partial application
- callable object
- function annotations
- function attributes
- function introspection

## 57. Python 高级对象机制

- attribute lookup
- __getattribute__
- __getattr__
- __setattr__
- __delattr__
- descriptor
- property
- class creation
- metaclass
- MRO

## 58. Python 数据模型

- Data Model
- object protocol
- container protocol
- iterator protocol
- callable protocol
- context manager protocol
- numeric protocol
- comparison protocol
- descriptor protocol
- async protocol

## 59. Python 协议

- iterable protocol
- iterator protocol
- sequence protocol
- mapping protocol
- context manager protocol
- descriptor protocol
- numeric protocol
- async iterator protocol
- async context manager protocol

## 60. Python 性能相关

- 时间复杂度
- 空间复杂度
- list 性能
- dict 性能
- set 性能
- 字符串性能
- 迭代器性能
- 生成器性能
- 拷贝性能
- 函数调用开销
- 内存占用
- functools.cache
- __slots__
- 性能分析

## 61. Python 常见高级工具

- itertools
- functools
- operator
- collections
- contextlib
- dataclasses
- enum
- typing
- inspect
- functools
- weakref

## 62. Python 现代特性

- f-string
- type hints
- dataclass
- enum
- walrus operator
- match / case
- positional-only parameters
- keyword-only parameters
- async / await
- async generator
- Protocol
- TypedDict
- TypeVar
- Generic
- Self
- ParamSpec
- TypeVarTuple
- ExceptionGroup
