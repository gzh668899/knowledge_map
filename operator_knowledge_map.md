# 算子 Operator 知识地图

## 1. 算子基础
- 什么是算子
- 算子的数学表达
- 算子的输入
- 算子的输出
- 算子的参数
- 算子的 Attribute
- 算子的计算过程
- 算子的 Shape
- 算子的 Data Type
- 算子的计算量
- 算子的计算复杂度

## 2. Tensor 与算子
- Tensor
- Scalar
- Vector
- Matrix
- Tensor Shape
- Tensor Rank
- Tensor Dimension
- Tensor Element
- Tensor Data Type
- Tensor Layout
- Tensor Stride
- Broadcasting
- Static Shape
- Dynamic Shape

## 3. 基础数学算子
- Add
- Sub
- Mul
- Div
- Neg
- Abs
- Sign
- Reciprocal
- Square
- Sqrt
- Rsqrt
- Pow
- Exp
- Log
- Sin
- Cos
- Tan
- Tanh

## 4. 比较与逻辑算子
- Equal
- NotEqual
- Greater
- GreaterEqual
- Less
- LessEqual
- LogicalAnd
- LogicalOr
- LogicalNot
- LogicalXor
- Where
- Select

## 5. 激活算子
- ReLU
- ReLU6
- LeakyReLU
- PReLU
- ELU
- SELU
- GELU
- SiLU
- Swish
- Mish
- Softplus
- Softsign
- Sigmoid
- Tanh
- HardSigmoid
- HardSwish

## 6. Reduction 算子
- ReduceSum
- ReduceMean
- ReduceMax
- ReduceMin
- ReduceProd
- ReduceL1
- ReduceL2
- ReduceLogSum
- ReduceLogSumExp
- ArgMax
- ArgMin
- Reduction Axis
- KeepDims

## 7. Shape 算子
- Reshape
- Flatten
- Squeeze
- Unsqueeze
- Expand
- ExpandDims
- Tile
- Broadcast
- Shape
- Size
- Rank

## 8. 数据变换算子
- Transpose
- Permute
- Cast
- Contiguous
- View
- Slice
- Split
- Chunk
- Concat
- Stack
- Unbind
- Pad
- Roll
- Repeat

## 9. Index / Gather / Scatter 算子
- Gather
- GatherND
- GatherElements
- Scatter
- ScatterND
- ScatterElements
- IndexSelect
- IndexPut
- Embedding
- OneHot

## 10. Convolution 算子
- Conv1D
- Conv2D
- Conv3D
- Standard Convolution
- Depthwise Convolution
- Pointwise Convolution
- Group Convolution
- Dilated Convolution
- Transposed Convolution
- Deformable Convolution

### Convolution 参数
- Kernel Size
- Stride
- Padding
- Dilation
- Groups
- Input Channels
- Output Channels
- Bias

## 11. Pooling 算子
- MaxPool
- AveragePool
- GlobalMaxPool
- GlobalAveragePool
- AdaptiveMaxPool
- AdaptiveAveragePool

## 12. Normalization 算子
- BatchNorm
- LayerNorm
- InstanceNorm
- GroupNorm
- RMSNorm
- Local Response Normalization

### Normalization 参数
- Mean
- Variance
- Standard Deviation
- Epsilon
- Scale
- Bias
- Affine

## 13. Linear Algebra 算子
- MatMul
- GEMM
- GEMV
- Dot
- Inner Product
- Outer Product
- Batch MatMul
- Transpose
- Diagonal
- Inverse
- Determinant
- Trace

## 14. Softmax 系列算子
- Softmax
- LogSoftmax
- Softmin
- Softmax Dimension
- Stable Softmax
- LogSumExp

## 15. Attention 算子
- Q
- K
- V
- QKᵀ
- Scale
- Softmax
- Attention × V
- Self-Attention
- Cross-Attention
- Multi-Head Attention
- Multi-Query Attention
- Grouped-Query Attention
- Causal Attention
- Masked Attention

## 16. Transformer 常见算子
- Linear
- MatMul
- Add
- LayerNorm
- RMSNorm
- Softmax
- GELU
- SiLU
- Embedding
- Positional Encoding
- RoPE
- Attention Mask
- Causal Mask
- SwiGLU

## 17. CNN 常见算子组合
- Conv + Bias
- Conv + ReLU
- Conv + BN
- Conv + BN + ReLU
- DepthwiseConv + PointwiseConv
- Conv + Activation
- Pooling + Activation

## 18. Arithmetic / Element-wise 组合算子
- Add + Activation
- Mul + Activation
- Bias + Activation
- Add + Mul
- Add + LayerNorm
- Bias + GELU
- Residual Add
- Gated Activation

## 19. Loss 算子
- MSELoss
- L1Loss
- SmoothL1Loss
- CrossEntropyLoss
- NLLLoss
- BCELoss
- BCEWithLogitsLoss
- KLDivLoss
- CosineEmbeddingLoss
- Hinge Loss

## 20. Probability / Sampling 算子
- Bernoulli
- Multinomial
- Normal
- Uniform
- Random
- RandomNormal
- RandomUniform
- TopK
- Sort
- Argsort

## 21. Padding 算子
- Zero Padding
- Constant Padding
- Reflect Padding
- Replicate Padding
- Circular Padding
- Same Padding
- Valid Padding

## 22. Quantization 相关算子
- Quantize
- Dequantize
- FakeQuantize
- Requantize
- Clamp
- Scale
- Zero Point
- Quantized Add
- Quantized Mul
- Quantized Conv
- Quantized MatMul

## 23. 常见融合算子
- Conv + Bias
- Conv + Activation
- Conv + BN
- Conv + BN + Activation
- Linear + Bias
- Linear + Activation
- MatMul + Bias
- Add + LayerNorm
- Add + RMSNorm
- QKV Fusion
- Attention Fusion
- Softmax Fusion

## 24. 算子属性
- Input
- Output
- Weight
- Bias
- Axis
- Dim
- KeepDims
- Shape
- Stride
- Padding
- Dilation
- Groups
- Kernel Size
- Epsilon
- Momentum
- Activation
- Data Type

## 25. 算子 Shape 推导
- 输入 Shape 推导
- 输出 Shape 推导
- Broadcast Shape
- Conv Shape
- Pooling Shape
- MatMul Shape
- Batch MatMul Shape
- Reduce Shape
- Reshape Shape
- Transpose Shape
- Concat Shape
- Split Shape
- Slice Shape
- Gather Shape

## 26. 算子计算复杂度
- 时间复杂度
- 空间复杂度
- FLOPs
- MACs
- 参数量
- 激活值数量
- 内存访问量
- 计算量
- Arithmetic Intensity

## 27. 算子数值计算
- Floating Point
- Fixed Point
- FP32
- FP16
- BF16
- INT8
- INT4
- 数值精度
- 数值范围
- Overflow
- Underflow
- Saturation
- Rounding
- Numerical Stability
- Approximation

## 28. 算子梯度
- Forward
- Backward
- Gradient
- Partial Derivative
- Chain Rule
- Jacobian
- Gradient Propagation
- 自动微分
- 算子反向传播

## 29. 典型算子深入原理
- Conv 数学原理
- MatMul 数学原理
- Softmax 数学原理
- LayerNorm 数学原理
- RMSNorm 数学原理
- BatchNorm 数学原理
- Pooling 数学原理
- Attention 数学原理
- GELU 数学原理
- SiLU 数学原理
- RoPE 数学原理

## 30. 算子性能基础
- Compute Bound
- Memory Bound
- Memory Access
- Cache
- Cache Locality
- Data Reuse
- Vectorization
- Parallelism
- Tiling
- Blocking
- Kernel Launch Overhead
- Latency
- Throughput

## 31. 算子正确性
- 输入合法性
- Shape Check
- Data Type Check
- 数值正确性
- 边界条件
- NaN
- Inf
- 精度误差
- Reference Implementation
- Golden Data
- Numerical Comparison
- Unit Test

## 32. 算子学习重点

### 第一阶段：基础
- Tensor
- Shape
- Data Type
- Broadcasting
- Element-wise
- Reduction
- Shape Operators

### 第二阶段：核心算子
- Conv
- Pooling
- BatchNorm
- LayerNorm
- MatMul
- Softmax
- Activation

### 第三阶段：Transformer 算子
- Attention
- QKV
- MatMul
- Softmax
- LayerNorm
- RMSNorm
- RoPE
- SwiGLU

### 第四阶段：深入
- 算子数学原理
- Shape 推导
- FLOPs
- Memory Access
- Numerical Stability
- Forward / Backward
- 算子性能
- 算子融合

### 第五阶段：算子体系
- Element-wise
- Reduction
- Shape
- Data Movement
- Convolution
- Pooling
- Normalization
- Linear Algebra
- Activation
- Attention
- Loss
- Sampling
- Quantization
- Fused Operators
