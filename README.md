# CUDA-Torch-GPU-RTX3070
CUDA-Torch-GPU-RTX3070

# First, an intro to GPU RTX3070 with Pytorch:

![image](https://user-images.githubusercontent.com/30595158/223591104-d92127bc-a41f-4c19-bd15-d3137878d744.png)

https://en.wikipedia.org/wiki/GeForce_30_series

Nsight Compute 2023.1.0
Nsight Systems 2023.1.2
Nsight Monitor

Set these traces.  Set hotkey to F2.  Add python backtrace

![image](https://user-images.githubusercontent.com/30595158/223607018-fd00fc13-c7f6-41bb-811e-903b045a0760.png)


- **MNLI (Multi-Genre Natural Language Inference)** 🗣️💬
  - evaluates how well a model understands relationships between sentences 👥💭
  - dataset has over 400,000 sentence pairs from different genres 📚📖
  - model needs to classify relationship as:
    - Entailment: hypothesis is true based on premise ✅
    - Contradiction: hypothesis is false based on premise ❌
    - Neutral: not enough info to determine the truth/falsity of hypothesis 🤷
  - accuracy metric used to evaluate model's performance 📊
  - pre-trained language models (like BERT or RoBERTa) are typically used and fine-tuned on MNLI dataset to make accurate predictions
  
- **CUDA Trace** 📈
  - tool for profiling and optimizing CUDA applications 🔍
  - records information about kernel launches, memory transfers, and other CUDA events 📝
  - helps identify performance bottlenecks 🕵️‍♀️
  - need to add profiling code, compile with CUDA compiler, and run with NVIDIA Visual Profiler 👨‍💻
  
- **GPU Metrics** 🎛️
  - provides detailed information about performance of GPU (utilization, memory usage, temperature) 📊🌡️💾
  - can monitor with NVIDIA System Monitor, GPU-Z, or MSI Afterburner 👀
  - helps identify performance issues and optimize applications for GPU 🚀
  
- **NVTX Trace** 📉
  - tool for profiling and debugging CUDA applications 🔍🐛
  - allows annotation of code with custom markers 📌
  - helps identify performance bottlenecks 🕵️‍♂️
  - can be used with profiling tools like NVIDIA Nsight Systems or NVIDIA Visual Profiler 👨‍💻
  
- **WDDM Trace** 📊
  - tool for profiling Windows Display Driver Model (WDDM) graphics drivers 🔍🖥️
  - records information about graphics events (rendering, presenting, synchronization) 📝
  - helps identify performance issues 🕵️‍♀️
  - can be used with Windows Performance Analyzer tool 👨‍💻
  
- **Python Backtrace Samples at Sampling Rate 1 kHz** 🐍📈
  - tool for profiling Python applications 🔍
  - records information about function call stack 📝
  - helps identify performance bottlenecks 🕵️‍♂️
  - can capture with tools like py-spy or perf 💻
  - sampling at 1 kHz means profiler takes a sample every millisecond for high-resolution view of performance ⏱️
  
Overall, these tools can help identify performance issues and optimize applications for better performance on GPU or CPU. 🚀

# Deep Learning Libraries

1. NVIDIA cuDNN 🧠💻
- GPU-accelerated library of primitives for deep neural networks
2. NVIDIA TensorRT™ 🚀🤖
- High-performance deep learning inference optimizer and runtime for production deployment
3. NVIDIA Riva 🗣️🤖
- Platform for developing engaging and contextual AI-powered conversation apps
4. NVIDIA DeepStream SDK 📹🤖
- Real-time streaming analytics toolkit for AI-based video understanding and multi-sensor processing
5. NVIDIA DALI 🎥💪
- Portable, open-source library for decoding and augmenting images and videos to accelerate deep learning applications


