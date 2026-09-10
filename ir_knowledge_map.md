# 模型表示 / IR 知识地图

## 1. 模型表示基础
- 什么是模型表示
- 什么是 IR（Intermediate Representation）
- 为什么需要模型表示
- 模型表示的作用
- 模型表示的层级
- 模型表示与模型文件
- 模型表示与计算图
- 模型表示与算子
- 模型表示与 Tensor
- 模型表示与权重
- 模型表示与模型结构
- 模型表示与模型语义

## 2. Tensor 表示
- Tensor
- Tensor Shape
- Tensor Rank
- Tensor Dimension
- Tensor Data Type
- Tensor Layout
- Tensor Stride
- Tensor Element
- Tensor Size
- Tensor Shape 信息
- Static Shape
- Dynamic Shape
- Symbolic Shape
- Tensor Type
- Tensor 元数据

## 3. Graph 表示
- Computational Graph
- Graph
- Node
- Edge
- Input
- Output
- Intermediate Tensor
- Constant
- Parameter
- Initializer
- Node Dependency
- Graph Connectivity
- Graph Topology
- Subgraph
- Graph Input
- Graph Output

## 4. Operator 表示
- Operator
- Operator Type
- Operator Schema
- Operator Input
- Operator Output
- Operator Attribute
- Operator Parameter
- Operator Domain
- Operator Version
- Operator Constraint
- Operator Semantics

## 5. 权重表示
- Weight
- Bias
- Parameter
- Constant
- Initializer
- Weight Tensor
- Weight Shape
- Weight Data Type
- Weight Storage
- Weight Metadata
- Shared Weight

## 6. Attribute 表示
- Attribute
- Integer Attribute
- Float Attribute
- String Attribute
- Boolean Attribute
- Integer List
- Float List
- String List
- Shape Attribute
- Data Type Attribute
- Attribute Default Value

## 7. Type System
- Tensor Type
- Scalar Type
- Integer Type
- Floating Point Type
- Boolean Type
- String Type
- Shape Type
- Sequence Type
- Optional Type
- Tuple Type
- Type Inference
- Type Checking
- Type Compatibility

## 8. Shape 表示
- Shape
- Rank
- Dimension
- Static Dimension
- Dynamic Dimension
- Symbolic Dimension
- Unknown Dimension
- Shape Inference
- Shape Propagation
- Shape Constraint
- Shape Compatibility
- Shape Validation

## 9. Layout 表示
- Tensor Layout
- Memory Layout
- NCHW
- NHWC
- CHW
- HWC
- NLC
- NCL
- NCDHW
- NDHWC
- Layout Attribute
- Layout Transformation
- Dimension Order

## 10. Data Type 表示
- FP32
- FP16
- BF16
- FP64
- INT64
- INT32
- INT16
- INT8
- INT4
- UINT8
- BOOL
- Data Type Conversion
- Type Casting
- Mixed Precision

## 11. 常量表示
- Constant
- Scalar Constant
- Tensor Constant
- Constant Folding 所需的常量
- Constant Attribute
- Constant Tensor
- Immutable Value

## 12. Value 表示
- Value
- SSA Value
- Use
- Def
- Producer
- Consumer
- Value Definition
- Value Use
- Value Lifetime
- Value Dependency

## 13. SSA 表示
- SSA（Static Single Assignment）
- SSA Value
- Value Definition
- Use-Def Chain
- Def-Use Chain
- Basic Block
- Block Argument
- Phi
- SSA Property

## 14. IR 层级

### 14.1 高层 IR
- Model Level IR
- Graph Level IR
- Neural Network IR
- High-Level Operator
- Model Semantics

### 14.2 中层 IR
- Tensor IR
- Operator IR
- Graph IR
- Structured Operation
- Tensor Transformation

### 14.3 低层 IR
- Low-Level IR
- Primitive Operation
- Memory Operation
- Loop
- Load
- Store
- Address
- Buffer
- Hardware-Oriented Operation

## 15. IR Operation
- Operation
- Operation Name
- Operation Input
- Operation Output
- Operation Result
- Operation Operand
- Operation Attribute
- Operation Region
- Operation Trait
- Operation Type
- Operation Constraint

## 16. Region / Block
- Region
- Block
- Basic Block
- Block Argument
- Operation List
- Control Flow
- Nested Region
- Region Argument

## 17. Dialect
- Dialect
- Operation Definition
- Type Definition
- Attribute Definition
- Dialect Namespace
- Built-in Dialect
- Custom Dialect
- Dialect Conversion
- Dialect Compatibility

## 18. Graph 拓扑
- Directed Graph
- DAG
- Node Dependency
- Topological Order
- Producer
- Consumer
- Fan-in
- Fan-out
- Dependency Chain
- Graph Traversal

## 19. Subgraph
- Subgraph
- Nested Graph
- Graph Partition
- Graph Region
- Function
- Function Call
- Control Flow Subgraph
- Conditional Subgraph
- Loop Subgraph

## 20. 模型结构表示
- Sequential Model
- Functional Model
- Static Graph
- Dynamic Graph
- Feed Forward Graph
- Residual Connection
- Skip Connection
- Branch
- Merge
- Loop
- Conditional

## 21. 模型格式

### 21.1 PyTorch
- PyTorch Model
- TorchScript
- FX Graph
- FX Node
- FX GraphModule
- ExportedProgram
- ATen Operator

### 21.2 ONNX
- ONNX Model
- ONNX Graph
- ONNX Node
- ONNX Tensor
- ONNX Attribute
- ONNX Initializer
- ONNX ValueInfo
- ONNX Opset
- ONNX Operator Schema

### 21.3 TensorFlow
- GraphDef
- NodeDef
- TensorProto
- FunctionDef
- SavedModel

### 21.4 TFLite / LiteRT
- FlatBuffer
- Model
- SubGraph
- Operator
- Tensor
- Buffer
- Operator Code

### 21.5 其他 IR / 模型表示
- MLIR
- StableHLO
- Torch IR
- TOSA
- TensorRT Network
- OpenVINO IR

## 22. 模型导出表示
- Model Export
- Graph Extraction
- Operator Extraction
- Parameter Extraction
- Constant Extraction
- Input / Output Extraction
- Dynamic Shape Export
- Static Shape Export
- Model Serialization

## 23. 模型序列化
- Serialization
- Deserialization
- Model File
- Binary Format
- Text Format
- FlatBuffer
- Protobuf
- JSON
- Metadata
- Version
- Compatibility

## 24. IR 验证
- IR Validation
- Schema Validation
- Type Validation
- Shape Validation
- Graph Validation
- Operator Validation
- Attribute Validation
- Input / Output Validation
- Topology Validation
- Model Consistency

## 25. IR 中的模型信息
- Model Metadata
- Model Version
- Producer
- Domain
- Graph Name
- Operator Set
- Input Information
- Output Information
- Tensor Information
- Shape Information
- Data Type Information

## 26. IR 表示的典型问题
- Operator 不支持
- Operator Schema 不匹配
- Attribute 不匹配
- Data Type 不匹配
- Shape 不匹配
- Dynamic Shape
- Layout 不匹配
- Opset 不兼容
- Version 不兼容
- Graph 不合法
- Tensor 类型错误
- Input / Output 不匹配

## 27. IR 的核心概念

### 必须掌握
- Graph
- Node
- Edge
- Tensor
- Value
- Operator
- Attribute
- Parameter
- Constant
- Input
- Output
- Shape
- Data Type
- Layout

### 进一步掌握
- SSA
- Operation
- Region
- Block
- Type System
- Dialect
- Subgraph
- Symbolic Shape
- Shape Inference
- Graph Topology

### 模型格式
- PyTorch FX
- TorchScript
- ONNX
- GraphDef
- TFLite / LiteRT
- MLIR
- StableHLO

## 28. 最终形成的模型表示结构

```
Model
├── Metadata
├── Graph
│   ├── Inputs
│   ├── Outputs
│   ├── Nodes / Operations
│   │   ├── Inputs
│   │   ├── Outputs
│   │   ├── Attributes
│   │   └── Type
│   ├── Initializers / Parameters
│   └── Constants
├── Tensors
│   ├── Shape
│   ├── Data Type
│   └── Layout
└── Subgraphs / Functions
    ├── Regions
    └── Blocks
```
