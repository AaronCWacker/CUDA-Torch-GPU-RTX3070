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

MNLI (Multi-Genre Natural Language Inference) is a benchmark dataset and task that evaluates a model's ability to perform natural language inference (NLI). NLI is the task of determining whether a given hypothesis can be inferred from a given premise.

In the MNLI task, the model is presented with a premise sentence and a hypothesis sentence, and it has to classify the relationship between them as one of three categories:

Entailment: the hypothesis is true based on the premise.
Contradiction: the hypothesis is false based on the premise.
Neutral: there is not enough information to determine the truth or falsity of the hypothesis based on the premise.
The dataset contains over 400,000 sentence pairs from ten different genres, such as fiction, telephone speech, and government documents, making it a challenging and diverse benchmark for evaluating NLI models.

The MNLI task is evaluated using the accuracy metric, which measures the proportion of sentence pairs that the model correctly classifies.

To train a model for the MNLI task, a typical approach is to use a pre-trained language model, such as BERT or RoBERTa, and fine-tune it on the MNLI dataset using a supervised learning approach. During fine-tuning, the model learns to make accurate predictions by adjusting its internal parameters based on the labeled examples in the dataset.

Overall, the MNLI task serves as a useful benchmark for evaluating the ability of natural language processing models to understand and reason about the relationships between sentences.

CUDA trace: CUDA trace is a tool for profiling and optimizing CUDA applications. It records information about kernel launches, memory transfers, and other CUDA events to help identify performance bottlenecks. To use CUDA trace, you need to add profiling code to your application, compile it with the CUDA compiler, and then run the application with the NVIDIA Visual Profiler.

GPU Metrics: GPU metrics provide detailed information about the performance of your GPU, such as the GPU utilization, memory usage, and temperature. You can monitor GPU metrics using various tools, such as NVIDIA System Monitor, GPU-Z, or MSI Afterburner. Monitoring GPU metrics can help you identify performance issues and optimize your application for the GPU.

NVTX Trace: NVTX trace is a tool for profiling and debugging CUDA applications. It allows you to annotate your code with custom markers to help identify performance bottlenecks. NVTX trace can be used with various profiling tools, such as NVIDIA Nsight Systems or NVIDIA Visual Profiler.

WDDM Trace: WDDM trace is a tool for profiling Windows Display Driver Model (WDDM) graphics drivers. It records information about graphics events, such as rendering, presenting, and synchronization, to help identify performance issues. WDDM trace can be used with the Windows Performance Analyzer tool.

Python backtrace samples at sampling rate 1 kHz: Python backtrace samples are a tool for profiling Python applications. They record information about the function call stack to help identify performance bottlenecks. You can capture Python backtrace samples using various tools, such as py-spy or perf. Sampling at a rate of 1 kHz means that the profiler takes a sample every millisecond, providing a high-resolution view of the application's performance.

Overall, these profiling and tracing tools can help you identify performance issues and optimize your applications for better performance on the GPU or CPU.
