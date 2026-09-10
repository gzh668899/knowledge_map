# C++ 知识地图

## 00. C++ 基础

### C++ 程序结构

- main 函数
- 头文件
- 源文件
- 预处理指令
- 命名空间

- 注释
- 标识符
- 关键字

### 字面量

- 整数字面量
- 浮点数字面量
- 字符字面量
- 字符串字面量
- 布尔字面量
- nullptr

- 变量
- 常量
- 表达式
- 语句
- 作用域

## 01. 数据类型

### 基本类型

- bool
- char
- wchar_t
- char8_t
- char16_t
- char32_t
- short
- int
- long
- long long
- float
- double
- long double

- signed / unsigned
- 类型大小与范围

### 类型别名

- typedef
- using

- auto
- decltype
- std::nullptr_t
- void

## 02. 类型转换

- 隐式类型转换
- 显式类型转换
- C 风格转换
- static_cast
- const_cast
- reinterpret_cast
- dynamic_cast
- 数值类型转换
- 整数提升
- 整数转换
- 浮点转换
- 指针类型转换

## 03. 运算符

- 算术运算符
- 关系运算符
- 逻辑运算符
- 位运算符
- 赋值运算符
- 自增自减
- 条件运算符
- 逗号运算符
- sizeof
- alignof
- typeid
- new / delete
- 成员访问运算符
- 下标运算符
- 函数调用运算符
- 运算符优先级

## 04. 流程控制

- if
- if / else
- else if
- switch
- case
- default
- for
- while
- do while
- range-based for
- break
- continue
- goto

## 05. 函数

- 函数声明
- 函数定义
- 函数调用

### 参数

- 值传递
- 指针传递
- 引用传递

- 返回值
- 返回类型
- 默认参数
- 函数重载
- 函数签名
- 函数作用域
- inline
- constexpr 函数
- consteval 函数
- constinit
- noexcept 函数
- 尾置返回类型
- 函数指针

## 06. 引用

- 左值引用
- 右值引用
- 引用初始化
- 引用作为参数
- 引用作为返回值
- const 引用
- 引用折叠
- 万能引用 / 转发引用

## 07. 指针

- 指针基础
- 指针变量
- 取地址
- 解引用
- nullptr
- 空指针
- 野指针
- 悬空指针

### const 与指针

- 指向 const 的指针
- const 指针
- 指向 const 的 const 指针

- 指针运算
- 指针与数组
- 指针与函数
- 多级指针
- void*
- 成员指针

## 08. 数组与字符串

- C 风格数组
- 一维数组
- 多维数组
- 数组初始化
- 数组大小
- 数组与指针
- 数组作为函数参数
- 字符数组
- C 风格字符串
- 字符串字面量
- std::string

## 09. const / constexpr

- const 变量
- const 指针
- const 引用
- const 成员函数
- const 成员变量
- constexpr 变量
- constexpr 函数
- constexpr 构造函数
- consteval
- constinit
- const-correctness

## 10. 类与对象

- class
- struct
- 对象
- 成员变量
- 成员函数
- public
- private
- protected
- this 指针
- 类内初始化
- 静态成员
- const 成员函数
- mutable
- 嵌套类

### 友元

- friend 函数
- friend 类
- friend 模板

- 类的前置声明

## 11. 构造与析构

- 默认构造函数
- 普通构造函数
- 参数化构造函数
- 拷贝构造函数
- 移动构造函数
- 委托构造
- 转换构造函数
- explicit
- 析构函数
- 构造函数初始化列表
- 成员初始化顺序
- 基类初始化
- delegating constructor
- = default
- = delete

## 12. 拷贝与移动

- 拷贝初始化
- 拷贝赋值
- 移动初始化
- 移动赋值
- 拷贝构造
- 移动构造
- 深拷贝
- 浅拷贝
- Rule of Three
- Rule of Five
- Rule of Zero
- std::move
- std::forward
- 完美转发

## 13. 面向对象

- 封装

### 继承

- 单继承
- 多继承
- 多重继承
- public 继承
- protected 继承
- private 继承

- 多态
- 虚函数
- virtual
- override
- final
- 纯虚函数
- 抽象类
- 虚析构函数
- 静态绑定
- 动态绑定
- 对象切片
- 基类指针
- 基类引用
- RTTI
- dynamic_cast

## 14. 运算符重载

- 运算符重载基础
- 成员运算符重载
- 非成员运算符重载
- 一元运算符
- 二元运算符
- ++ / --
- + / -
- == / !=
- <=>
- << / >>
- []
- ()
- ->
- =
- 类型转换运算符

## 15. 内存管理

- 栈对象
- 堆对象
- 静态存储
- new
- delete
- new[]
- delete[]
- placement new
- 内存泄漏
- 悬空指针
- double free
- use-after-free
- 对齐
- std::align
- 对象生命周期
- 存储期

## 16. 智能指针

### std::unique_ptr

- 独占所有权
- move
- release
- reset
- custom deleter

### std::shared_ptr

- 引用计数
- use_count
- reset
- make_shared
- custom deleter

### std::weak_ptr

- weak reference
- lock
- 循环引用

- std::make_unique
- std::make_shared
- 所有权语义

## 17. 命名空间

- namespace
- namespace 嵌套
- 匿名命名空间
- namespace alias
- using namespace
- using 声明
- using 指令

## 18. 预处理器

- #include
- #define
- #undef
- #if
- #ifdef
- #ifndef
- #elif
- #else
- #endif
- #pragma
- 宏函数
- 条件编译
- include guard

## 19. 异常

- exception
- throw
- try
- catch
- 多个 catch
- catch(...)
- 异常传播
- 异常重新抛出
- 自定义异常
- noexcept
- exception hierarchy

### 异常安全

- no-throw guarantee
- strong guarantee
- basic guarantee

## 20. STL 容器

### sequence containers

- array
- vector
- deque
- list
- forward_list

### associative containers

- set
- multiset
- map
- multimap

### unordered containers

- unordered_set
- unordered_multiset
- unordered_map
- unordered_multimap

### container adaptors

- stack
- queue
- priority_queue

- 容器选择

## 21. STL 迭代器

- iterator
- const_iterator
- reverse_iterator
- const_reverse_iterator
- 输入迭代器
- 输出迭代器
- 前向迭代器
- 双向迭代器
- 随机访问迭代器
- contiguous iterator
- iterator_traits
- begin / end
- rbegin / rend

## 22. STL 算法

### 查找

- find
- find_if
- binary_search

### 排序

- sort
- stable_sort
- partial_sort
- nth_element

### 遍历

- for_each
- transform

### 修改

- copy
- move
- fill
- replace
- erase

- 比较
- 数值算法
- 集合算法
- 堆算法
- 排列算法

## 23. STL 常用工具

- std::pair
- std::tuple
- std::optional
- std::variant
- std::any
- std::function
- std::bind
- std::reference_wrapper
- std::bitset
- std::ratio
- std::type_traits

## 24. 字符串

- std::string
- std::wstring
- std::u8string
- std::u16string
- std::u32string
- string_view
- 字符串构造
- 字符串访问
- 字符串修改
- 字符串查找
- 字符串比较
- 字符串转换
- std::format

## 25. 输入输出

- iostream
- cin
- cout
- cerr
- clog
- ostream
- istream
- stringstream
- istringstream
- ostringstream

### 文件流

- ifstream
- ofstream

- 格式化输出
- std::format

## 26. Lambda

- Lambda 基础
- Lambda 参数
- Lambda 返回值

### 捕获

- []
- [=]
- [&]
- [this]
- [*this]

- mutable Lambda
- 泛型 Lambda
- constexpr Lambda
- Lambda 与 std::function
- Lambda 类型

## 27. 函数对象与回调

- 函数对象
- function object
- function pointer
- std::function
- bind
- placeholders
- Lambda 回调

## 28. 模板

- 函数模板
- 类模板

### 模板参数

- 类型参数
- 非类型参数
- 模板参数

- 模板实例化

### 模板特化

- 全特化
- 偏特化

- 函数模板重载
- 默认模板参数
- 模板参数推导
- 显式模板参数
- 模板别名
- 模板成员

## 29. 模板高级

- 类型萃取
- type_traits
- SFINAE
- enable_if
- void_t
- detection idiom
- constexpr if
- Concepts
- requires
- constraint
- variadic templates
- parameter pack
- pack expansion
- fold expression
- CRTP

## 30. C++20 Concepts

- concept
- requires expression
- requires clause
- 类型约束
- 参数约束
- 组合约束
- 标准 Concepts
- Concepts 与 SFINAE

## 31. 泛型编程

- 泛型函数
- 泛型类
- 类型参数化
- 值参数化
- Traits
- Policy
- Concepts
- CRTP
- 编译期多态

## 32. 左值 / 右值

- lvalue
- rvalue
- xvalue
- prvalue
- glvalue
- 临时对象
- 生命周期
- 移动语义
- std::move
- 完美转发

## 33. 对象生命周期

- 对象创建
- 对象初始化
- 对象销毁
- 生命周期
- 临时对象
- 生命周期延长
- placement new
- 显式析构
- 对象重用
- storage duration

## 34. 初始化

- 默认初始化
- 值初始化
- 零初始化
- 直接初始化
- 拷贝初始化
- 列表初始化
- 聚合初始化
- 初始化列表
- std::initializer_list
- 初始化顺序

## 35. 类型系统高级

- 强类型
- 类型推导
- auto
- decltype
- decltype(auto)
- 类型别名
- 类型萃取
- std::is_same
- std::is_base_of
- std::is_convertible
- std::is_constructible
- std::common_type

## 36. C++ 编译期编程

- constexpr
- consteval
- constinit
- constexpr 变量
- constexpr 函数
- constexpr 构造
- constexpr if
- static_assert
- type_traits
- 模板元编程
- Concepts
- 编译期计算

## 37. STL 内存与分配器

- allocator
- allocator_traits
- allocator-aware containers
- polymorphic_allocator
- memory_resource
- monotonic_buffer_resource
- pool resource
- 自定义分配器

## 38. STL 容器高级机制

- vector 扩容
- vector iterator invalidation
- deque 内部结构
- list 节点
- map
- set
- 红黑树
- unordered_map
- 哈希表
- bucket
- load factor
- rehash
- iterator invalidation

## 39. C++ 并发

- thread
- jthread
- mutex
- recursive_mutex
- timed_mutex
- shared_mutex
- lock_guard
- unique_lock
- shared_lock
- scoped_lock
- condition_variable
- future
- promise
- async
- packaged_task
- atomic
- atomic_flag
- memory_order
- semaphore
- latch
- barrier
- stop_token

## 40. C++ 内存模型

- thread of execution
- data race
- race condition
- happens-before
- synchronizes-with
- sequenced-before
- atomic operation
- memory_order_relaxed
- memory_order_acquire
- memory_order_release
- memory_order_acq_rel
- memory_order_seq_cst
- memory fence

## 41. 并发高级

- lock-free
- wait-free
- ABA problem
- 无锁数据结构
- 原子智能指针
- 并发容器
- 线程池
- task system
- coroutine 与并发

## 42. 协程

- coroutine 基础
- co_await
- co_yield
- co_return
- coroutine frame
- promise_type
- coroutine_handle
- awaiter
- awaitable
- suspend_always
- suspend_never
- generator

## 43. C++ 模块

- module
- module interface
- module implementation
- import
- export
- module partition
- header unit

## 44. C++20 / C++23 新特性

### C++11

- auto
- nullptr
- lambda
- range-for
- move semantics
- smart pointer
- constexpr

### C++14

- generic lambda
- relaxed constexpr

### C++17

- structured binding
- if constexpr
- fold expression
- optional
- variant
- any
- string_view
- filesystem

### C++20

- Concepts
- Ranges
- Coroutines
- Modules
- Three-way comparison
- std::span
- std::jthread
- std::format
- std::source_location
- std::stop_token
- synchronization primitives

### C++23

- std::expected
- std::print
- std::generator
- ranges enhancements
- deducing this
- multidimensional subscript
- constexpr enhancements

## 45. Ranges

- range
- view
- iterator
- std::ranges

### views

- filter
- transform
- take
- drop
- reverse
- join

- range adaptor
- pipe operator
- concepts
- range algorithms

## 46. 文件与路径

- std::filesystem
- path
- directory
- file status
- file operations
- directory iteration
- 文件时间

## 47. 日期与时间

- chrono
- duration
- time_point
- clock
- system_clock
- steady_clock
- high_resolution_clock
- time zone
- calendar

## 48. 随机数

- random engine
- random device
- seed

### distribution

- uniform
- normal
- bernoulli
- poisson

- 随机数生成

## 49. 正则表达式

- regex
- regex_match
- regex_search
- regex_replace
- match_results
- regex_iterator

## 50. C++ 库设计

- API 设计
- 接口与实现分离
- PImpl
- ABI
- ODR
- 头文件设计
- 前置声明
- 依赖管理
- ownership
- value semantics / reference semantics

## 51. C++ 高级对象模型

- 对象模型
- 对象表示
- 对象生命周期
- 内存布局
- 空对象
- 成员变量布局
- 基类布局
- 多继承布局
- 虚函数表
- 虚指针
- RTTI
- 对象切片
- 类型擦除

## 52. 类型擦除

- type erasure
- std::any
- std::function
- 虚函数实现
- Concept / Model
- 小对象优化
- 自定义类型擦除

## 53. Undefined Behavior

- UB 基础
- 越界访问
- 空指针解引用
- 悬空引用
- 生命周期违规
- strict aliasing
- 有符号整数溢出
- 未初始化读取
- data race
- UB 与编译器优化

## 54. C++ 性能

- 拷贝成本
- 移动成本
- RVO
- NRVO
- 临时对象
- 内存分配
- vector 性能
- cache locality
- branch
- inline
- virtual dispatch
- allocation strategy
- zero-cost abstraction

## 55. C++ 设计模式

### 创建型

- Factory
- Abstract Factory
- Builder
- Singleton

### 结构型

- Adapter
- Bridge
- Composite
- Decorator
- Facade
- Proxy

### 行为型

- Observer
- Strategy
- Command
- State
- Visitor
- Template Method
- Chain of Responsibility

## 56. Modern C++ 编程思想

- RAII
- Ownership
- Resource Management
- Value Semantics
- Move Semantics
- Zero-Cost Abstraction
- Generic Programming
- Compile-Time Programming
- Type Safety
- Exception Safety
- Concurrency Safety
- Rule of Zero
- Prefer RAII
- Prefer value semantics
- Prefer composition
- Resource ownership 设计
