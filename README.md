# 数字信号处理实践 · FIR 数字滤波器的 FPGA 实现

使用 MATLAB 完成 61 阶线性相位 FIR 低通滤波器设计与 12 bit 系数量化，并使用 Verilog 实现 RTL；采用线性相位对称结构将乘法器数量由 61 个减少到 31 个，降低 FPGA 硬件资源占用。

## 功能

- 61 阶线性相位 FIR 低通滤波器设计
- 12 bit 系数量化与频响验证
- 线性相位对称结构优化（乘法器 61 → 31）
- Verilog RTL 实现、Quartus II 综合与 ModelSim 时序仿真

## 技术栈

MATLAB、Verilog、Quartus II、ModelSim、Cyclone IV FPGA

## 目录

- `docs/DSP课程设计报告.doc`：课程实践报告（设计原理、MATLAB 设计流程、系数量化、对称结构优化、仿真结果与结论）
- `src/`：Verilog RTL 与工程文件（如仓库提供）

## 说明

本仓库为数字信号处理课程实践成果，核心设计流程、参数与验证结果见报告。
