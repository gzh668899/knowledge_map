# AI Compiler 知识地图

## 1. AI Compiler 基础
- 什么是 AI Compiler
- AI Compiler 与传统 Compiler 的区别
- AI Model
- Model Graph
- Tensor
- Operator
- Graph
- IR
- Compiler Pipeline
- Frontend
- Middle-end
- Backend
- Codegen
- Hardware Mapping

## 2. AI Compiler 整体编译流程
- Model Import
- Model Parsing
- Graph Construction
- Graph Optimization
- IR Generation
- IR Optimization
- Operator Transformation
- Lowering
- Scheduling
- Memory Optimization
- Code Generation
- Hardware Mapping

## 3. Model Graph
- Computational Graph
- Graph Node
- Graph Edge
- Tensor
- Operator
- Input
- Output
- Constant
- Parameter
- Weight
- Bias
- Graph Topology
- Graph Traversal
- Subgraph
- Graph Partition

## 4. Tensor
- Tensor
- Tensor Rank
- Tensor Dimension
- Tensor Shape
- Tensor Element
- Tensor Data Type
- Tensor Layout
- Tensor Stride
- Tensor Size
- Tensor Memory
- Static Shape
- Dynamic Shape
- Symbolic Shape

## 5. Operator
- Operator
- Operator Input
- Operator Output
- Operator Attribute
- Operator Schema
- Operator Semantics
- Operator Shape Function
- Operator Type
- Element-wise Operator
- Reduction Operator
- Convolution
- Matrix Multiplication
- Pooling
- Activation
- Normalization
- Reshape
- Transpose
- Gather
- Scatter
- Attention

## 6. Model Import
- Model Import
- Model Parser
- Model Loader
- Graph Import
- Operator Mapping
- Tensor Mapping
- Attribute Mapping
- Constant Import
- Weight Import
- Model Validation
- Unsupported Operator
- Import Error

## 7. AI Compiler IR
- Intermediate Representation
- Graph IR
- Tensor IR
- Operator IR
- High-Level IR
- Mid-Level IR
- Low-Level IR
- IR Operation
- IR Value
- IR Type
- IR Attribute
- IR Block
- IR Region
- IR Graph
- IR Module

## 8. SSA
- Static Single Assignment
- SSA Value
- Definition
- Use
- Use-Def Chain
- Def-Use Chain
- Phi
- Basic Block
- Dominance
- Dominator

## 9. Dialect
- Dialect
- Operation Definition
- Type Definition
- Attribute Definition
- Dialect Interface
- Custom Dialect
- High-Level Dialect
- Tensor Dialect
- Linalg Dialect
- Affine Dialect
- Vector Dialect
- Low-Level Dialect
- Dialect Conversion

## 10. Shape System
- Shape
- Shape Inference
- Shape Propagation
- Shape Function
- Static Shape
- Dynamic Shape
- Symbolic Shape
- Shape Constraint
- Shape Checking
- Shape Simplification
- Shape Specialization
- Shape Folding

## 11. Layout System
- Tensor Layout
- Memory Layout
- Logical Layout
- Physical Layout
- Layout Transformation
- Layout Conversion
- Layout Propagation
- Layout Assignment
- Layout Constraint
- Data Reordering
- Stride
- Contiguous Layout

## 12. Graph Analysis
- Graph Analysis
- Topological Sort
- Dependency Analysis
- Data Dependency
- Control Dependency
- Producer
- Consumer
- Dominance
- Reachability
- Dead Node
- Constant Node
- Graph Pattern

## 13. Graph Optimization
- Graph Optimization
- Graph Rewrite
- Graph Simplification
- Constant Folding
- Constant Propagation
- Dead Node Elimination
- Redundant Node Elimination
- Common Subexpression Elimination
- Operator Elimination
- Operator Replacement
- Graph Canonicalization

## 14. Operator Fusion
- Operator Fusion
- Fusion Pattern
- Fusion Rule
- Fusion Group
- Producer-Consumer Fusion
- Element-wise Fusion
- Vertical Fusion
- Horizontal Fusion
- Convolution Fusion
- MatMul Fusion
- Activation Fusion
- Kernel Fusion
- Fusion Constraint
- Fusion Benefit
- Fusion Cost

## 15. Operator Decomposition
- Operator Decomposition
- Composite Operator
- Primitive Operator
- Decomposition Rule
- Pattern Decomposition
- High-Level Operator
- Low-Level Operator
- Operator Expansion
- Operator Replacement

## 16. Canonicalization
- Canonicalization
- Canonical Form
- Rewrite Rule
- Simplification
- Algebraic Simplification
- Redundant Operation Elimination
- Pattern Matching
- Pattern Rewrite
- Normalization

## 17. Constant Optimization
- Constant Folding
- Constant Propagation
- Constant Evaluation
- Constant Hoisting
- Constant Deduplication
- Constant Elimination
- Weight Transformation

## 18. Graph Partition
- Graph Partitioning
- Subgraph Partitioning
- Partition Boundary
- Supported Operator
- Unsupported Operator
- Subgraph
- Partition Strategy
- Graph Cut
- Dependency Boundary
- Partition Cost

## 19. Lowering
- Lowering
- High-Level IR
- Mid-Level IR
- Low-Level IR
- Progressive Lowering
- Operation Lowering
- Type Lowering
- Shape Lowering
- Layout Lowering
- Memory Lowering
- Control Flow Lowering
- Hardware-specific Lowering

## 20. Legalization
- Legalization
- Legal Operation
- Illegal Operation
- Conversion Target
- Conversion Pattern
- Operation Conversion
- Type Conversion
- Partial Conversion
- Full Conversion
- Dynamic Legality

## 21. Loop Transformation
- Loop
- Loop Nest
- Loop Transformation
- Loop Interchange
- Loop Fusion
- Loop Fission
- Loop Tiling
- Loop Unrolling
- Loop Peeling
- Loop Distribution
- Loop Interchange
- Loop Permutation
- Loop Skewing

## 22. Tiling
- Tiling
- Tile
- Tile Size
- Tile Shape
- Multi-Level Tiling
- Loop Tiling
- Tensor Tiling
- Matrix Tiling
- Convolution Tiling
- Memory Tile
- Compute Tile
- Tiling Strategy
- Tiling Cost Model

## 23. Scheduling
- Scheduling
- Operation Scheduling
- Instruction Scheduling
- Execution Order
- Dependency
- Dependency Graph
- Parallel Execution
- Sequential Execution
- Pipeline
- Software Pipelining
- Schedule Optimization
- Scheduling Constraint

## 24. Parallelism
- Parallelism
- Data Parallelism
- Tensor Parallelism
- Operator Parallelism
- Loop Parallelism
- Thread Parallelism
- SIMD
- Vectorization
- Task Parallelism
- Pipeline Parallelism
- Synchronization
- Dependency Constraint

## 25. Vectorization
- Vectorization
- Scalar Operation
- Vector Operation
- Vector Width
- SIMD
- Vector Instruction
- Loop Vectorization
- SLP Vectorization
- Reduction Vectorization
- Vector Dependency
- Vectorization Cost Model

## 26. Memory Optimization
- Memory Optimization
- Buffer
- Buffer Allocation
- Bufferization
- Memory Planning
- Memory Reuse
- Buffer Reuse
- Buffer Lifetime
- Lifetime Analysis
- In-place Operation
- Out-of-place Operation
- Memory Alias
- Memory Access Pattern

## 27. Data Movement
- Data Movement
- Memory Transfer
- Tensor Movement
- Buffer Copy
- DMA
- Memory Bandwidth
- Data Locality
- Producer-Consumer Locality
- Data Reuse
- Copy Elimination
- Copy Fusion

## 28. Memory Layout Optimization
- Layout Optimization
- Layout Transformation
- Layout Propagation
- Layout Conversion
- Data Reordering
- Memory Access Pattern
- Strided Access
- Contiguous Access
- Cache Locality
- Local Memory
- Shared Memory
- On-chip Memory

## 29. Kernel
- Kernel
- Kernel Operation
- Kernel Fusion
- Kernel Generation
- Kernel Template
- Kernel Parameter
- Kernel Launch
- Kernel Scheduling
- Kernel Tiling
- Kernel Vectorization
- Kernel Specialization

## 30. Code Generation
- Code Generation
- Codegen
- Kernel Codegen
- Instruction Selection
- Instruction Scheduling
- Register Allocation
- Instruction Emission
- Target Code
- Assembly
- Machine Code

## 31. Hardware Mapping
- Hardware Mapping
- Operator Mapping
- Tensor Mapping
- Compute Unit Mapping
- Memory Mapping
- Execution Mapping
- Parallelism Mapping
- Hardware Constraint
- Hardware Capability
- Target-specific Optimization

## 32. Hardware-aware Optimization
- Hardware-aware Optimization
- Compute Throughput
- Memory Bandwidth
- Memory Latency
- Compute-to-Memory Ratio
- Data Locality
- Register Pressure
- Occupancy
- Parallelism
- Hardware Utilization
- Hardware Cost Model

## 33. Cost Model
- Cost Model
- Compute Cost
- Memory Cost
- Data Movement Cost
- Operator Cost
- Fusion Cost
- Tiling Cost
- Scheduling Cost
- Latency
- Throughput
- Memory Bandwidth
- Code Size
- Register Pressure
- Optimization Benefit

## 34. Quantitative Optimization
- Latency Optimization
- Throughput Optimization
- Memory Optimization
- Compute Optimization
- Bandwidth Optimization
- Operator Cost
- Kernel Cost
- Fusion Benefit
- Tiling Benefit
- Scheduling Benefit
- Optimization Trade-off

## 35. Dynamic Shape Compiler
- Dynamic Shape
- Symbolic Shape
- Shape Constraint
- Shape Expression
- Runtime Shape
- Shape Specialization
- Shape Guard
- Shape Dispatch
- Dynamic Compilation
- Shape-dependent Optimization

## 36. Static Shape Compiler
- Static Shape
- Compile-time Shape
- Shape Propagation
- Shape Specialization
- Constant Shape
- Static Memory Planning
- Static Scheduling
- Static Optimization

## 37. Quantization相关编译优化
- Quantized Tensor
- Quantized Operator
- Quantization-aware Graph
- Quantized IR
- Integer Operator
- Mixed Precision
- Quantized Kernel
- Quantization Lowering
- Quantization Rewrite
- Quantization Fusion

## 38. AI Compiler 中的 Pass
- Pass
- Pass Pipeline
- Analysis Pass
- Transformation Pass
- Optimization Pass
- Conversion Pass
- Lowering Pass
- Scheduling Pass
- Codegen Pass
- Pass Ordering
- Pass Dependency
- Pass Manager

## 39. AI Compiler Debug
- IR Dump
- IR Visualization
- Graph Visualization
- Pass Debugging
- Transformation Debugging
- Lowering Debugging
- Codegen Debugging
- Compiler Trace
- Intermediate Result
- Compiler Diagnostic
- Compiler Error

## 40. AI Compiler 正确性
- Compiler Correctness
- Graph Equivalence
- Operator Equivalence
- Numerical Correctness
- Transformation Correctness
- Lowering Correctness
- Codegen Correctness
- Reference Implementation
- Golden Model
- Differential Testing

## 41. AI Compiler 测试
- Unit Test
- Operator Test
- Graph Test
- IR Test
- Pass Test
- Lowering Test
- Codegen Test
- Regression Test
- Golden Test
- Differential Test
- Random Test
- Fuzz Test

## 42. MLIR 在 AI Compiler 中的作用
- MLIR
- Operation
- Value
- Type
- Attribute
- Block
- Region
- SSA
- Dialect
- Pattern Rewrite
- Pass
- Canonicalization
- Conversion
- Lowering
- Verification

## 43. AI Compiler 常见 IR 层次

```
Model Graph
↓
High-Level IR
↓
Tensor / Operator IR
↓
Linalg / Structured IR
↓
Loop IR
↓
Vector IR
↓
Low-Level IR
↓
Machine / Target IR
↓
Codegen
```

## 44. AI Compiler 核心编译链路

```
Model
↓
Graph Import
↓
Graph IR
↓
Shape / Type Inference
↓
Graph Optimization
↓
Operator Fusion
↓
Operator Decomposition
↓
Layout Optimization
↓
Lowering
↓
Tiling
↓
Scheduling
↓
Memory Optimization
↓
Kernel Generation
↓
Codegen
↓
Hardware Mapping
```

## 45. AI Compiler 最核心知识

### 第一阶段：AI Compiler 基础
- Model Graph
- Tensor
- Operator
- Graph
- IR
- Compiler Pipeline

### 第二阶段：AI IR
- Operation
- Value
- Type
- Attribute
- Block
- Region
- SSA
- Dialect

### 第三阶段：Graph Optimization
- Graph Rewrite
- Constant Folding
- Dead Node Elimination
- Operator Fusion
- Operator Decomposition
- Canonicalization
- Graph Partition

### 第四阶段：Tensor / Layout
- Shape
- Shape Inference
- Dynamic Shape
- Layout
- Layout Transformation
- Layout Propagation

### 第五阶段：Lowering
- High-Level IR
- Mid-Level IR
- Low-Level IR
- Legalization
- Dialect Conversion
- Operation Lowering

### 第六阶段：Performance Optimization
- Tiling
- Loop Transformation
- Vectorization
- Scheduling
- Memory Optimization
- Data Movement
- Kernel Optimization

### 第七阶段：Codegen
- Kernel Generation
- Instruction Selection
- Instruction Scheduling
- Register Allocation
- Code Generation
- Hardware Mapping

### 第八阶段：高级 AI Compiler
- Dynamic Shape Compilation
- Hardware-aware Optimization
- Cost Model
- Auto Tuning
- Graph Partitioning
- Quantized Graph Compilation
- Compiler Correctness
- Compiler Testing
