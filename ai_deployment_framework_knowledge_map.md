# AI 部署框架 AI Deployment Framework 知识地图

## 1. AI 部署框架基础
- 什么是 AI 部署框架
- Model Deployment
- Training
- Inference
- Deployment Framework
- Inference Framework
- Deployment Runtime
- Backend
- Device
- Hardware Acceleration
- CPU
- GPU
- NPU
- DSP
- Edge Device
- Mobile Device
- Server

## 2. AI 部署整体链路
- Model
- Model Conversion
- Model Representation
- Model Optimization
- Model Compilation
- Backend Selection
- Runtime Execution
- Hardware Execution
- Result

## 3. 模型来源
- PyTorch
- TensorFlow
- JAX
- ONNX
- Hugging Face
- Custom Model
- Pretrained Model
- Training Framework
- Model Checkpoint

## 4. 模型格式
- PyTorch Model
- TorchScript
- ONNX
- TensorFlow SavedModel
- TensorFlow Lite
- FlatBuffer
- Safetensors
- GGUF
- Custom Model Format
- Intermediate Model Format
- Deployment Model Format

## 5. 模型转换
- Model Conversion
- Export
- Import
- Converter
- Graph Conversion
- Operator Conversion
- Tensor Conversion
- Attribute Conversion
- Data Type Conversion
- Layout Conversion
- Model Validation
- Unsupported Operator

## 6. 模型优化
- Model Optimization
- Graph Optimization
- Operator Fusion
- Operator Decomposition
- Constant Folding
- Dead Node Elimination
- Layout Optimization
- Memory Optimization
- Quantization
- Model Simplification

## 7. Backend
- Backend
- Backend Abstraction
- Backend Selection
- Backend Registration
- Backend Capability
- Operator Support
- Backend Dispatch
- CPU Backend
- GPU Backend
- NPU Backend
- DSP Backend
- Custom Backend

## 8. Delegate / Provider
- Delegate
- Delegate Backend
- Hardware Delegate
- CPU Delegate
- GPU Delegate
- NPU Delegate
- Execution Provider
- Execution Provider Registration
- Execution Provider Selection
- Operator Support
- Fallback

## 9. Operator 支持
- Operator Support
- Supported Operator
- Unsupported Operator
- Operator Version
- Operator Attribute
- Operator Constraint
- Operator Coverage
- Operator Compatibility
- Operator Fallback
- Custom Operator

## 10. Graph Partition
- Graph Partition
- Subgraph
- Partition
- Partition Boundary
- Backend Partition
- Operator Partition
- Supported Subgraph
- Unsupported Subgraph
- Partition Strategy
- Fallback Partition

## 11. Fallback
- Backend Fallback
- CPU Fallback
- Operator Fallback
- Unsupported Operator
- Partial Acceleration
- Fallback Graph
- Fallback Execution
- Fallback Cost
- Cross-backend Execution

## 12. Tensor / Data
- Tensor
- Shape
- Data Type
- Layout
- Stride
- Buffer
- Input Tensor
- Output Tensor
- Intermediate Tensor
- Dynamic Shape
- Static Shape

## 13. Input / Output
- Input Binding
- Output Binding
- Tensor Binding
- Buffer Binding
- Input Shape
- Output Shape
- Dynamic Input
- Dynamic Output
- Zero-copy
- Shared Buffer

## 14. Hardware Abstraction
- Device Abstraction
- Hardware Abstraction
- Device Selection
- Device Capability
- CPU
- GPU
- NPU
- DSP
- Accelerator
- Hardware Backend

## 15. Mobile AI 部署
- Android
- iOS
- Mobile SoC
- Mobile CPU
- Mobile GPU
- Mobile NPU
- Device Memory
- Shared Memory
- Power Consumption
- Thermal Constraint
- Performance Constraint
- Offline Inference

## 16. 边缘 AI 部署
- Edge AI
- Edge Device
- Embedded Device
- Mobile Device
- IoT Device
- On-device AI
- Offline Inference
- Low Latency
- Low Power
- Limited Memory
- Hardware Acceleration

## 17. LLM 部署
- LLM Inference
- Transformer Model
- Decoder-only Model
- Prefill
- Decode
- KV Cache
- Tokenization
- Detokenization
- Context Length
- Batch
- Continuous Batching
- Streaming
- Model Sharding

## 18. LLM 部署框架
- llama.cpp
- ExecuTorch
- LiteRT
- ONNX Runtime
- MNN
- TensorRT
- vLLM
- MLX
- Transformers
- Custom LLM Runtime

## 19. 主流端侧部署框架

### LiteRT
- LiteRT
- LiteRT Runtime
- LiteRT Converter
- LiteRT Delegate
- LiteRT GPU
- LiteRT NPU
- LiteRT CPU
- LiteRT Model Format

### ExecuTorch
- ExecuTorch
- PyTorch Export
- Edge IR
- Backend
- Delegate
- Partitioning
- Lowering
- Runtime
- EValue
- Program

### ONNX Runtime
- ONNX Runtime
- ONNX Model
- Execution Provider
- CPU EP
- CUDA EP
- TensorRT EP
- QNN EP
- NNAPI EP
- CoreML EP
- Operator Kernel

### MNN
- MNN
- MNN Converter
- MNN Runtime
- MNN Express
- MNN Backend
- CPU Backend
- GPU Backend
- NPU Backend
- Model Format

### llama.cpp
- llama.cpp
- GGUF
- GGML
- CPU Backend
- GPU Backend
- Quantized Model
- KV Cache
- Batch
- Token Generation

## 20. 部署框架架构
- Frontend
- Model Import
- Model Representation
- Converter
- Graph Optimization
- Backend
- Delegate
- Execution Engine
- Runtime
- Hardware

## 21. Framework API
- Model API
- Session API
- Interpreter API
- Tensor API
- Backend API
- Delegate API
- Execution API
- Device API
- Custom Operator API
- Custom Backend API

## 22. 模型生命周期
- Model Export
- Model Conversion
- Model Optimization
- Model Packaging
- Model Loading
- Runtime Initialization
- Input Binding
- Inference
- Output Retrieval
- Resource Release

## 23. 部署产物
- Model File
- Optimized Model
- Compiled Model
- Backend Binary
- Kernel Binary
- Weight File
- Configuration File
- Metadata
- Model Package
- Deployment Package

## 24. 模型兼容性
- Model Compatibility
- Operator Compatibility
- Version Compatibility
- Data Type Compatibility
- Shape Compatibility
- Layout Compatibility
- Backend Compatibility
- Hardware Compatibility
- API Compatibility
- Model Format Compatibility

## 25. 自定义扩展
- Custom Operator
- Custom Kernel
- Custom Backend
- Custom Delegate
- Custom Execution Provider
- Custom Device
- Backend Extension
- Operator Registration
- Kernel Registration

## 26. 性能优化
- Latency
- Throughput
- FPS
- QPS
- Memory Usage
- Peak Memory
- Power Consumption
- CPU Usage
- GPU Usage
- NPU Utilization
- Data Transfer
- Warm-up
- End-to-End Performance

## 27. 部署性能分析
- Benchmark
- Profiling
- Operator Profiling
- Model Profiling
- Backend Profiling
- Memory Profiling
- Timeline
- Trace
- Latency Analysis
- Bottleneck Analysis

## 28. 端侧部署限制
- Memory Constraint
- Compute Constraint
- Power Constraint
- Thermal Constraint
- Storage Constraint
- Model Size
- Startup Time
- Latency Constraint
- Throughput Constraint
- Hardware Compatibility

## 29. 部署版本管理
- Model Version
- Framework Version
- Backend Version
- Runtime Version
- Hardware Version
- Operator Version
- Compatibility Matrix
- Model Migration
- API Compatibility

## 30. 多硬件部署
- CPU Deployment
- GPU Deployment
- NPU Deployment
- DSP Deployment
- Heterogeneous Computing
- Hardware Selection
- Backend Selection
- Device Fallback
- Multi-device Execution

## 31. 部署框架生态
- Open Source Framework
- Proprietary Framework
- Community
- Hardware Vendor
- Model Ecosystem
- Backend Ecosystem
- Operator Ecosystem
- Toolchain
- Documentation
- Community Support

## 32. 开源端侧框架
- LiteRT
- ExecuTorch
- ONNX Runtime
- MNN
- llama.cpp
- ncnn
- TNN
- NCNN
- MediaPipe
- OpenVINO
- Apache TVM

## 33. 硬件厂商部署生态
- Qualcomm
- Samsung
- MediaTek
- NVIDIA
- Apple
- Google
- Intel
- AMD
- Huawei
- Arm

## 34. AI 部署框架选型
- Model Type
- Device Type
- Hardware Backend
- Operator Coverage
- Model Format
- Performance
- Memory Usage
- Power Consumption
- Ecosystem
- Community
- Hardware Support
- Customization
- Deployment Complexity

## 35. 部署框架对比维度
- Model Support
- Framework Support
- Model Format
- Converter
- Graph Optimization
- Backend Support
- Hardware Support
- Operator Coverage
- Quantization Support
- Dynamic Shape Support
- LLM Support
- Mobile Support
- Edge Support
- Community Activity

## 36. AI Deployment Framework 核心关系

```
Training Framework
↓
Model Export
↓
Model Format
↓
Deployment Framework
↓
Model Conversion
↓
Graph Optimization
↓
Backend / Delegate
↓
Runtime
↓
Hardware
↓
Inference
```

## 37. 端侧部署核心链路

```
PyTorch
↓
Export
↓
Deployment IR / Model Format
↓
Deployment Framework
↓
Graph Optimization
↓
Backend / Delegate
↓
Hardware
↓
Runtime Execution
```

## 38. AI 部署框架学习阶段

### 第一阶段：部署基础
- AI Deployment
- Model
- Model Format
- Converter
- Backend
- Runtime
- Hardware

### 第二阶段：模型接入
- Model Import
- Model Export
- Model Conversion
- Operator Mapping
- Tensor Mapping
- Model Validation

### 第三阶段：框架核心机制
- Backend
- Delegate
- Execution Provider
- Operator Support
- Graph Partition
- Fallback
- Custom Operator

### 第四阶段：端侧部署
- CPU
- GPU
- NPU
- DSP
- Device Abstraction
- Mobile Deployment
- Edge Deployment

### 第五阶段：性能
- Latency
- Throughput
- Memory
- Power
- Profiling
- Benchmark
- Bottleneck Analysis

### 第六阶段：框架生态
- LiteRT
- ExecuTorch
- ONNX Runtime
- MNN
- llama.cpp
- ncnn
- TVM
- OpenVINO
