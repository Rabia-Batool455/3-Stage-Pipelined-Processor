# 3-Stage-Pipelined-Processor

 ### Key Features
1. Three Pipeline Stages:
### Fetch (IF): The instruction is fetched from memory.
### Decode (ID): The fetched instruction is decoded, and operands are retrieved from registers.
### Execute (EX): The decoded instruction is executed, with results being computed and forwarded to memory or registers.
2. Improved Throughput:
The 3-stage pipeline increases the throughput by allowing multiple instructions to be processed simultaneously at different stages, improving overall instruction execution speed.
3. Simplified Design:
The processor design is straightforward with only three stages, making it easier to understand and implement compared to more complex multi-stage pipelines.
Independent Instruction Execution:
The processor is designed for handling independent instructions, enabling better utilization of resources and higher efficiency.
4. Modular Architecture:
Each pipeline stage is designed as a separate module, allowing for a clean, scalable architecture that follows the Single Responsibility Principle.
5. Basic Hazard Handling:
Since hazards are not explicitly managed, this design works best with independent instructions, making it suitable for simpler, academic use cases.
6. Suitability for Educational Purposes:
The 3-stage pipeline design is often used in educational settings for teaching the concepts of pipelining and processor architecture in a simplified form.
7. Low Latency and Power Efficient:
With fewer stages, the 3-stage pipeline tends to have lower latency and is more power-efficient compared to more complex designs with many pipeline stages.
