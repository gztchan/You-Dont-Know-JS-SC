# 你不知道的 JavaScript：异步与性能表现

# 第 4 章：Generators

在第 2 章的描述中，我们明确了使用 callback 进行异步流控制的两个关键缺点：
- 基于 callback 的异步控制与人脑计划进行任务的理解不相符。
- 因为 callback 对于控制的颠倒导致的可靠性低和组织性差。

在第 3 章内容中，详细地描述了 Promise 是如何理顺 callback 的颠倒控制的，从而恢复代码的可靠性和组织性。

接下来我们将会把重点放在如何使用 ES6 中 Generators 特性，去实现以连续的、看似同步执行的表达方式处理异步流控制。

## 打碎置顶向下代码的运行方式 (Breaking Run-to-Completion)

### 输入与输出 (Input and Output)

#### 迭代信息 (Iteration Messaging)

##### (Table of Two Questions)

### (Multiple Iterators)

#### (Interleaving)

## (Generatoring Values)

### (Producers and Iterators)

### (Iterables)

### (Generator Iterator)

#### (Stopping the Generator)

## Iterating Generators Asynchronously

### Synchronous Error Handling

## Generators + Promise

### Promise-Aware Generator Runner

### Promise Concurrency in Generators


#### Promises, Hidden

## Generator Delegation


### Why Delegation?


### Delegating Messages

### Delegating Asynchrony

### Delegating "Recursion"

## Generator Concurrency

## Thunks

## Pre-ES6 Generators

## Review


