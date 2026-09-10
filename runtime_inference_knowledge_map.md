# Runtime / Inference 知识地图

## 1. Runtime 基础
- 什么是 Runtime
- Inference Runtime
- Runtime 与 Compiler 的区别
- Runtime 与 Framework 的区别
- Runtime 与 Model 的关系
- Runtime 与 Hardware 的关系
- Runtime 生命周期
- Runtime Context
- Runtime Session
- Runtime Executor
- Runtime Pipeline

## 2. Inference 基础
- Inference
- Model Inference
- Input
- Output
- Tensor
- Operator
- Execution
- Inference Request
- Inference Session
- Inference Context
- Inference Result

## 3. Model Loading
- Model Loading
- Model File
- Model Format
- Model Parsing
- Model Deserialization
- Model Validation
- Model Metadata
- Model Graph
- Model Weight
- Model Parameter
- Model Initialization

## 4. Runtime Model Representation
- Runtime Graph
- Runtime Node
- Runtime Tensor
- Runtime Operator
- Runtime Value
- Runtime Attribute
- Input Tensor
- Output Tensor
- Constant Tensor
- Intermediate Tensor
- Graph Dependency

## 5. Execution Graph
- Execution Graph
- Graph Traversal
- Topological Order
- Dependency
- Producer
- Consumer
- Execution Order
- Graph Execution
- Subgraph
- Execution Partition

## 6. Execution Engine
- Execution Engine
- Executor
- Execution Plan
- Operator Execution
- Kernel Dispatch
- Execution Context
- Execution State
- Execution Queue
- Execution Dependency
- Execution Scheduler

## 7. Tensor 管理
- Tensor
- Tensor Shape
- Tensor Rank
- Tensor Data Type
- Tensor Layout
- Tensor Stride
- Tensor Size
- Tensor Buffer
- Tensor Lifetime
- Tensor Ownership
- Tensor Reference
- Tensor View

## 8. Memory Management
- Runtime Memory
- Memory Allocation
- Memory Deallocation
- Buffer Allocation
- Memory Pool
- Memory Arena
- Memory Planner
- Memory Reuse
- Buffer Reuse
- Memory Lifetime
- Peak Memory
- Memory Fragmentation

## 9. Memory Planning
- Static Memory Planning
- Dynamic Memory Planning
- Tensor Lifetime Analysis
- Buffer Lifetime
- Buffer Sharing
- Memory Reuse
- In-place Execution
- Out-of-place Execution
- Memory Allocation Strategy
- Memory Planning Strategy

## 10. Device Abstraction
- Device
- Device Abstraction
- Device Context
- Device Memory
- Host Memory
- Device Memory Allocation
- Device Initialization
- Device Capability
- Device Selection
- Device Synchronization

## 11. Execution Backend
- Backend
- Backend Abstraction
- Backend Interface
- Backend Initialization
- Backend Context
- Backend Executor
- Backend Capability
- Backend Operator Support
- Backend Dispatch
- Backend Fallback

## 12. Operator Execution
- Operator Execution
- Operator Kernel
- Kernel Dispatch
- Input Binding
- Output Binding
- Operator Context
- Operator Parameters
- Operator State
- Operator Execution Order
- Operator Error Handling

## 13. Kernel Dispatch
- Kernel
- Kernel Selection
- Kernel Dispatch
- Kernel Parameters
- Kernel Launch
- Execution Queue
- Command Submission
- Dispatch Configuration
- Dispatch Dependency

## 14. Queue / Stream
- Queue
- Command Queue
- Execution Queue
- Stream
- Compute Stream
- Copy Stream
- Queue Submission
- Queue Ordering
- Stream Ordering
- Multi-Stream Execution

## 15. Synchronization
- Synchronization
- Device Synchronization
- Host Synchronization
- Queue Synchronization
- Stream Synchronization
- Fence
- Event
- Barrier
- Dependency
- Blocking
- Non-blocking Execution

## 16. Asynchronous Execution
- Synchronous Execution
- Asynchronous Execution
- Async Inference
- Async Execution
- Callback
- Future
- Event
- Non-blocking API
- Pipeline Execution
- Overlap Execution

## 17. Data Transfer
- Host-to-Device
- Device-to-Host
- Device-to-Device
- Tensor Copy
- Buffer Copy
- Data Transfer
- Transfer Queue
- Transfer Synchronization
- Copy Elimination
- Data Movement

## 18. Inference Session
- Session
- Session Initialization
- Session Configuration
- Session Creation
- Session Destruction
- Session State
- Session Reuse
- Session Reset
- Session Thread Safety

## 19. Input / Output Binding
- Input Binding
- Output Binding
- Tensor Binding
- Buffer Binding
- Memory Binding
- Input Shape
- Output Shape
- Dynamic Input
- Output Allocation
- Zero-copy Binding

## 20. Dynamic Shape Runtime
- Dynamic Shape
- Runtime Shape
- Shape Validation
- Shape Propagation
- Shape-dependent Allocation
- Dynamic Memory Allocation
- Dynamic Execution
- Shape Dispatch
- Shape Specialization
- Dynamic Output

## 21. Batch Execution
- Batch
- Batch Size
- Static Batch
- Dynamic Batch
- Batch Inference
- Micro Batch
- Batch Scheduling
- Batch Memory
- Batch Latency
- Batch Throughput

## 22. Concurrency
- Concurrency
- Parallel Execution
- Thread Pool
- Worker Thread
- Task Queue
- Task Scheduling
- Multi-threading
- Multi-stream
- Request Concurrency
- Execution Concurrency

## 23. Inference Scheduling
- Inference Scheduler
- Request Scheduling
- Task Scheduling
- Priority
- Queue
- Scheduling Policy
- Dynamic Scheduling
- Static Scheduling
- Batch Scheduling
- Fairness
- Latency-aware Scheduling
- Throughput-aware Scheduling

## 24. Multi-request Inference
- Inference Request
- Request Queue
- Request Lifecycle
- Request Scheduling
- Request Batching
- Request Concurrency
- Request Isolation
- Request Cancellation
- Request Completion

## 25. Runtime Optimization
- Runtime Optimization
- Execution Optimization
- Memory Optimization
- Data Transfer Optimization
- Kernel Dispatch Optimization
- Scheduling Optimization
- Thread Optimization
- Memory Reuse
- Zero-copy
- Pipeline Optimization

## 26. Zero-copy
- Zero-copy
- Shared Buffer
- Shared Memory
- Buffer Sharing
- Memory Mapping
- Tensor View
- External Memory
- Import Buffer
- Export Buffer
- Copy Avoidance

## 27. Fallback
- Backend Fallback
- Operator Fallback
- Device Fallback
- Unsupported Operator
- Supported Operator
- Fallback Execution
- Fallback Path
- Execution Partition
- Fallback Cost
- Fallback Synchronization

## 28. Error Handling
- Runtime Error
- Model Error
- Tensor Error
- Shape Error
- Data Type Error
- Memory Error
- Device Error
- Execution Error
- Backend Error
- Timeout
- Error Propagation
- Error Recovery

## 29. Runtime State
- Runtime State
- Session State
- Execution State
- Tensor State
- Device State
- Kernel State
- Initialization State
- Running State
- Completion State
- Error State

## 30. Thread Safety
- Thread Safety
- Thread-safe API
- Shared Context
- Thread-local State
- Lock
- Mutex
- Atomic Operation
- Concurrent Access
- Resource Ownership
- Synchronization

## 31. Runtime API
- Runtime API
- Model API
- Session API
- Tensor API
- Memory API
- Device API
- Execution API
- Async API
- Event API
- Error API

## 32. Runtime 生命周期

```
Application
↓
Runtime Initialization
↓
Device Initialization
↓
Model Loading
↓
Session Creation
↓
Memory Allocation
↓
Input Binding
↓
Inference Execution
↓
Output Binding
↓
Result Retrieval
↓
Session Release
↓
Runtime Shutdown
```

## 33. Inference 执行链路

```
Input
↓
Input Tensor
↓
Input Binding
↓
Execution Graph
↓
Operator Scheduling
↓
Kernel Dispatch
↓
Device Execution
↓
Synchronization
↓
Output Tensor
↓
Output Retrieval
```

## 34. Runtime 性能指标
- Latency
- End-to-End Latency
- Operator Latency
- Kernel Latency
- Throughput
- FPS
- QPS
- Memory Usage
- Peak Memory
- CPU Usage
- Device Utilization
- Data Transfer Time
- Queue Time
- Synchronization Time

## 35. Latency
- Latency
- End-to-End Latency
- Compute Latency
- Memory Latency
- Transfer Latency
- Queue Latency
- Scheduling Latency
- Synchronization Latency
- Warm-up Latency
- Tail Latency

## 36. Throughput
- Throughput
- Requests Per Second
- Frames Per Second
- Batch Throughput
- Concurrent Throughput
- Device Throughput
- Compute Throughput
- Memory Throughput

## 37. Profiling
- Runtime Profiling
- Inference Profiling
- Operator Profiling
- Kernel Profiling
- Memory Profiling
- Timeline
- Trace
- CPU Profiling
- Device Profiling
- Queue Profiling
- Synchronization Profiling

## 38. Debug
- Runtime Debugging
- Graph Debugging
- Tensor Debugging
- Memory Debugging
- Execution Debugging
- Device Debugging
- Backend Debugging
- Runtime Logging
- Execution Trace
- Error Trace

## 39. Numerical Correctness
- Numerical Correctness
- Output Validation
- Reference Output
- Golden Output
- Numerical Error
- Absolute Error
- Relative Error
- Tolerance
- Operator Correctness
- End-to-End Correctness

## 40. Runtime 架构

```
Application
↓
Inference API
↓
Session
↓
Execution Engine
↓
Scheduler
↓
Backend
↓
Device
↓
Hardware
```

## 41. Runtime 核心关系

```
Model
↓
Model Loading
↓
Runtime Graph
↓
Session
↓
Tensor / Memory
↓
Execution Plan
↓
Scheduler
↓
Kernel Dispatch
↓
Device Execution
↓
Output
```

## 42. Runtime 学习阶段

### 第一阶段：Runtime 基础
- Runtime
- Inference
- Session
- Executor
- Execution Graph
- Tensor
- Operator

### 第二阶段：执行
- Execution Engine
- Execution Plan
- Operator Execution
- Kernel Dispatch
- Queue
- Stream
- Synchronization

### 第三阶段：内存
- Tensor Buffer
- Memory Allocation
- Memory Pool
- Memory Planning
- Memory Reuse
- Buffer Lifetime
- Zero-copy

### 第四阶段：并发
- Thread Pool
- Task Queue
- Multi-threading
- Multi-stream
- Async Execution
- Request Scheduling
- Batch Execution

### 第五阶段：高级 Runtime
- Dynamic Shape
- Backend Fallback
- Multi-request Inference
- Runtime Scheduling
- Device Abstraction
- Runtime Optimization

### 第六阶段：性能与调试
- Latency
- Throughput
- Memory Usage
- Profiling
- Timeline
- Trace
- Runtime Debugging
- Numerical Correctness
