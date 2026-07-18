# Hi, I'm Ishaan

Summer Intern @ Chipspirit Technologies | ECE Undergrad @ NIT

## What I Do

* Design **hardware-driven systems** using FPGAs & microcontrollers
* Develop **hardware acceleration** for convolutional neural networks (CNNs)
* Implement **complex DSP** algorithms using RTL

---

## Tech Stack

**Languages:** Verilog HDL, C/C++, Python, MathWorks MATLAB

**Hardware:** Xilinx Kria KV260, Digilent Arty a7-100t, Xilinx ZCU106

**EDA & Tools:** Vivado, VS Code, NI Multisim, MathWorks MATLAB, Arduino IDE, Proteus, Vivado, Vitis, Synopsys Sentarus TCAD, TeraTerm, MobaXTerm

---

## Featured Projects

**Hardware Accelerated Audio Fingerprinting**
* Architected a 100MHz zero-wait-state ZCU106 FPGA pipeline integrating a 1024-point AXI-Stream XFFT, 16-stage
Verilog CORDIC, and a cascading insertion sort network to dynamically extract top-5 frequency peaks.
* Engineered a cache-aligned AXI DMA architecture to continuously stream and compress audio into highly efficient 64-bit
temporal fingerprints while successfully bypassing OS bottlenecks. Deployed a fixed-point 1D Temporal CNN directly into
the hardware wrapper to classify the full 50-class ESC-50 dataset utilizing parallel MAC units and an optimized FSM.

**CNN Hardware Accelerator on Xilinx Kria KV260**
* Implemented a custom hardware accelerator achieving 98% accuracy and 8.85-microsecond latency, outperforming standard software models.
* Designed and implemented a high-performance, RTL-based CNN accelerator in Verilog for the AMD Kria KV260 FPGA,
achieving 98 per-cent accuracy on the MNIST dataset. Leveraged hardware acceleration to deliver an inference latency
of 8.85 mu/s image, resulting in a 150x throughput improvement compared to CPU-based implementations.

**8-point FFT Accelerator**
* Developed and implemented an 8 point Fast Fourier Transform Accelerator on pure RTL, handling various twiddle factor cases by pooling them accurately.
  
**IEEE-754 Hardware Multiplier**
* Developed discrete combinational RTL modules to execute standard floating-point arithmetic, including a 53-bit
multiplier yielding a 106-bit mantissa product, an 11-bit exponent adder with 1023 bias subtraction, and XOR-based
sign logic. Engineered a robust hardware exception-handling unit that systematically classifies inputs and resolves critical
IEEE-754 edge cases, ensuring mathematical stability for Not-a-Number (NaN), Infinity, zero, overflow, and underflow.
* Optimized the critical path for final product generation by routing the normalized outputs and exception flags through a
custom 5-to-1 multiplexer , ensuring deterministic data selection with zero latch inference.

---

## Connect with me 

* Linkedin:- https://www.linkedin.com/in/ishaan-panda-08974b323/
* GitHub:- https://github.com/1ishpan8
  


