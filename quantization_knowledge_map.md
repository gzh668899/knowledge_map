# 量化 Quantization 知识地图

## 1. 量化基础
- 什么是量化
- 为什么需要量化
- 量化的目的
- 模型量化
- 权重量化
- 激活量化
- 参数量化
- 量化前
- 量化后
- 浮点表示
- 整数表示
- 精度
- 模型大小
- 计算效率
- 内存占用

## 2. 数值表示基础
- 浮点数
- 整数
- 定点数
- Floating Point
- Fixed Point
- FP32
- FP16
- BF16
- INT32
- INT16
- INT8
- INT4
- UINT8
- 数值范围
- 数值精度
- 有效数字
- 小数位
- 动态范围

## 3. 浮点数基础
- Sign
- Exponent
- Mantissa
- IEEE 754
- FP32
- FP16
- BF16
- FP8
- 正数
- 负数
- Zero
- NaN
- Inf
- Subnormal
- Overflow
- Underflow
- Rounding

## 4. 整数表示
- Signed Integer
- Unsigned Integer
- INT8
- UINT8
- INT4
- UINT4
- INT16
- INT32
- Two's Complement
- Integer Range
- Zero
- Saturation

## 5. 量化核心概念
- Real Value
- Quantized Value
- Scale
- Zero Point
- Quantization Range
- Quantization Granularity
- Quantization Error
- Clamping
- Rounding
- Saturation
- Dequantization

## 6. Quantization / Dequantization

### Quantization
- Float → Integer
- Scale
- Zero Point
- Rounding
- Clamping

### Dequantization
- Integer → Float
- Scale
- Zero Point
- Approximate Reconstruction

### 核心公式
- q = round(x / scale) + zero_point
- x ≈ scale × (q - zero_point)

## 7. Scale
- Scale
- Scale Calculation
- Scale Range
- Per-Tensor Scale
- Per-Channel Scale
- Per-Group Scale
- Per-Token Scale
- Per-Block Scale
- Static Scale
- Dynamic Scale
- Symmetric Scale
- Asymmetric Scale

## 8. Zero Point
- Zero Point
- Zero Point Calculation
- Symmetric Zero Point
- Asymmetric Zero Point
- Zero Point = 0
- Integer Zero Point
- Floating Point Zero Point
- Zero Point 对齐

## 9. 对称量化
- Symmetric Quantization
- Symmetric Range
- Zero Point = 0
- Signed Integer
- Absolute Maximum
- Scale Calculation
- Weight Symmetric Quantization
- Activation Symmetric Quantization

## 10. 非对称量化
- Asymmetric Quantization
- Min / Max Range
- Zero Point
- Scale
- UINT8 Quantization
- Signed / Unsigned Range
- Zero Alignment

## 11. 量化粒度

### Per-Tensor
- Per-Tensor Quantization
- Single Scale
- Single Zero Point

### Per-Channel
- Per-Channel Quantization
- Channel Scale
- Channel Zero Point
- Weight Per-Channel Quantization

### Per-Group
- Per-Group Quantization
- Group Size
- Group Scale

### Per-Token
- Per-Token Quantization
- Token Scale

### Per-Block
- Per-Block Quantization
- Block Size
- Block Scale

## 12. Weight Quantization
- Weight Quantization
- Weight-Only Quantization
- Weight Scale
- Weight Zero Point
- Per-Tensor Weight Quantization
- Per-Channel Weight Quantization
- Per-Group Weight Quantization
- INT8 Weight
- INT4 Weight
- INT2 Weight

## 13. Activation Quantization
- Activation Quantization
- Activation Range
- Activation Scale
- Activation Zero Point
- Static Activation Quantization
- Dynamic Activation Quantization
- Per-Tensor Activation Quantization
- Per-Token Activation Quantization
- Outlier
- Activation Clipping

## 14. Bias Quantization
- Bias Quantization
- Bias Data Type
- INT32 Bias
- Bias Scale
- Bias Accumulation
- Bias Quantization Relationship

## 15. 静态量化
- Static Quantization
- Calibration
- Calibration Dataset
- Activation Statistics
- Min / Max
- Histogram
- Scale Estimation
- Zero Point Estimation
- Static Activation Scale

## 16. 动态量化
- Dynamic Quantization
- Runtime Range Estimation
- Dynamic Scale
- Dynamic Activation Quantization
- Weight Pre-Quantization
- Runtime Quantization

## 17. PTQ
- Post-Training Quantization
- PTQ
- Calibration
- Calibration Dataset
- Weight Quantization
- Activation Quantization
- Static PTQ
- Dynamic PTQ
- Weight-Only PTQ

## 18. QAT
- Quantization-Aware Training
- QAT
- Fake Quantization
- FakeQuant
- Straight-Through Estimator
- Quantization Simulation
- Forward Quantization
- Backward Gradient
- Quantization Noise

## 19. Fake Quantization
- FakeQuantize
- Quantize-Dequantize
- QDQ
- Fake Quantization Range
- Fake Scale
- Fake Zero Point
- Straight-Through Estimator
- Training-Time Quantization Simulation

## 20. Calibration
- Calibration
- Calibration Dataset
- Calibration Samples
- Activation Statistics
- Min-Max Calibration
- Percentile Calibration
- Histogram Calibration
- Entropy Calibration
- KL Divergence Calibration
- MSE Calibration
- Optimal Threshold
- Calibration Range

## 21. 量化范围
- Min
- Max
- Absolute Maximum
- Dynamic Range
- Quantization Range
- Clipping Range
- Threshold
- Symmetric Range
- Asymmetric Range
- Outlier
- Long-Tail Distribution

## 22. Clipping
- Clipping
- Clipping Range
- Clipping Threshold
- Symmetric Clipping
- Asymmetric Clipping
- Activation Clipping
- Weight Clipping
- Outlier Clipping
- Clipping Error

## 23. Rounding
- Rounding
- Round-to-Nearest
- Floor
- Ceil
- Truncation
- Stochastic Rounding
- Rounding Error
- Tie Breaking

## 24. Saturation
- Saturation
- Saturation Range
- Integer Saturation
- Overflow Saturation
- Clamping
- Saturation Error

## 25. 量化误差
- Quantization Error
- Rounding Error
- Clipping Error
- Reconstruction Error
- Absolute Error
- Relative Error
- Mean Squared Error
- Signal-to-Quantization-Noise Ratio
- SQNR
- Error Distribution

## 26. 量化精度
- Numerical Accuracy
- Model Accuracy
- Top-1 Accuracy
- Top-5 Accuracy
- Perplexity
- BLEU
- Task Metric
- FP32 Baseline
- Quantized Model Accuracy
- Accuracy Drop
- Accuracy Recovery

## 27. 混合精度
- Mixed Precision
- FP32 + FP16
- FP16 + INT8
- FP16 + INT4
- INT8 + INT4
- Layer-wise Precision
- Operator-wise Precision
- Mixed Precision Strategy
- Precision Allocation

## 28. 常见量化位宽
- FP32
- FP16
- BF16
- FP8
- INT16
- INT8
- INT6
- INT4
- INT3
- INT2
- Binary
- 1-bit Quantization

## 29. INT8 量化
- INT8
- Signed INT8
- Unsigned INT8
- INT8 Weight
- INT8 Activation
- INT8 Bias
- INT32 Accumulator
- INT8 Multiply
- INT8 Accumulation
- Requantization

## 30. INT4 量化
- INT4
- Weight INT4
- Activation INT4
- Weight-Only INT4
- Symmetric INT4
- Group-wise INT4
- Per-Group Scale
- INT4 Packing
- INT4 Dequantization
- INT4 MatMul

## 31. Weight-Only Quantization
- Weight-Only Quantization
- W8A16
- W4A16
- W3A16
- W2A16
- Quantized Weight
- Floating Point Activation
- Weight Packing
- Weight Dequantization
- Group-wise Quantization

## 32. LLM 量化
- LLM Quantization
- Weight Quantization
- Activation Quantization
- KV Cache Quantization
- W8A8
- W4A16
- W4A8
- Weight-Only Quantization
- SmoothQuant
- GPTQ
- AWQ
- RTN
- HQQ
- AQLM

## 33. KV Cache 量化
- KV Cache
- Key Quantization
- Value Quantization
- INT8 KV Cache
- INT4 KV Cache
- Per-Token KV Quantization
- Per-Channel KV Quantization
- KV Cache Scale
- KV Cache Accuracy

## 34. Outlier
- Outlier
- Activation Outlier
- Weight Outlier
- Channel Outlier
- Token Outlier
- Outlier Detection
- Outlier Suppression
- Outlier Migration
- Clipping
- Outlier-Aware Quantization

## 35. 量化感知分析
- Layer Sensitivity
- Operator Sensitivity
- Channel Sensitivity
- Weight Sensitivity
- Activation Sensitivity
- Quantization Sensitivity
- Accuracy Sensitivity
- Error Propagation
- Layer-wise Error
- Mixed Precision Selection

## 36. 量化误差传播
- Local Quantization Error
- Layer-wise Error
- Error Accumulation
- Error Propagation
- Activation Error
- Weight Error
- Output Error
- End-to-End Accuracy

## 37. 量化算子
- Quantize
- Dequantize
- FakeQuantize
- Requantize
- Quantized Add
- Quantized Mul
- Quantized Conv
- Quantized MatMul
- Quantized Linear
- QLinearConv
- QLinearMatMul

## 38. QDQ
- Quantize
- Dequantize
- QDQ Pattern
- QDQ Graph
- QDQ Placement
- QDQ Propagation
- QDQ Folding
- QDQ Representation

## 39. 量化计算
- Integer Arithmetic
- Integer Multiplication
- Integer Addition
- Accumulation
- INT32 Accumulator
- Requantization
- Scale Multiplication
- Fixed-Point Multiplication
- Integer Kernel

## 40. 量化中的矩阵乘法
- FP32 MatMul
- INT8 MatMul
- INT4 MatMul
- Quantized GEMM
- Quantized Accumulation
- Weight Quantization
- Activation Quantization
- Scale Handling
- Dequantization
- Requantization

## 41. 量化中的卷积
- FP32 Convolution
- INT8 Convolution
- INT4 Convolution
- Quantized Conv
- Weight Quantization
- Activation Quantization
- Bias
- INT32 Accumulation
- Requantization

## 42. 量化与 Normalization
- BatchNorm
- LayerNorm
- RMSNorm
- Quantization Before Normalization
- Quantization After Normalization
- Normalization Range
- Normalization Stability
- Norm Quantization

## 43. 量化与激活函数
- ReLU Quantization
- GELU Quantization
- SiLU Quantization
- Sigmoid Quantization
- Tanh Quantization
- Softmax Quantization
- Activation Range
- Activation Clipping

## 44. 量化方案
- W8A8
- W8A16
- W4A16
- W4A8
- W4A4
- W3A16
- W2A16
- Weight-Only
- Full Integer Quantization
- Mixed Precision

## 45. 量化工具与框架概念
- Quantization API
- Quantization Configuration
- Quantization Observer
- Fake Quantizer
- Calibration
- Quantization Backend
- Quantization Scheme
- Quantization Specification
- Quantization Mapping

## 46. 量化常见问题
- Accuracy Drop
- Quantization Error
- Calibration Failure
- Scale 不合理
- Zero Point 不合理
- Outlier
- Overflow
- Underflow
- Saturation
- Clipping
- Numerical Instability
- Operator 不支持量化
- Layer Sensitivity

## 47. 量化学习核心公式

### 线性量化
- q = round(x / scale) + zero_point

### 反量化
- x ≈ scale × (q - zero_point)

### 对称量化
- zero_point = 0
- scale = max(|x|) / max(|q|)

### 量化误差
- Error = x - x_quantized

### 量化范围
- Integer Range
- Real Value Range
- Scale Mapping

## 48. 量化学习阶段

### 第一阶段：基础
- 浮点数
- 整数
- FP32
- FP16
- BF16
- INT8
- INT4
- 数值范围
- 精度

### 第二阶段：核心量化
- Quantization
- Dequantization
- Scale
- Zero Point
- Rounding
- Clamping
- Saturation
- Quantization Error

### 第三阶段：量化方式
- Symmetric Quantization
- Asymmetric Quantization
- Per-Tensor
- Per-Channel
- Per-Group
- Per-Token
- Per-Block

### 第四阶段：实际量化
- Weight Quantization
- Activation Quantization
- Bias Quantization
- Static Quantization
- Dynamic Quantization
- PTQ
- QAT
- Calibration
- Fake Quantization

### 第五阶段：深入
- INT8
- INT4
- Weight-Only Quantization
- W8A8
- W4A16
- Mixed Precision
- Outlier
- Clipping
- Quantization Error Propagation
- Layer Sensitivity

### 第六阶段：LLM 量化
- GPTQ
- AWQ
- SmoothQuant
- RTN
- KV Cache Quantization
- W4A16
- W8A8
- Group-wise Quantization
- Per-Token Quantization
